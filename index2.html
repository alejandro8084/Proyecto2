//evento para crear un nuevo libro
document.getElementById("formulario").addEventListener("submit", crear);

$("#newVehicleYear").datepicker({
  format: "yyyy",
  viewMode: "years",
  minViewMode: "years",
  autoclose: true, //to close picker once year is selected
});

$("#vehicleYear").datepicker({
  format: "yyyy",
  viewMode: "years",
  minViewMode: "years",
  autoclose: true, //to close picker once year is selected
});

//funcion crear

function crear(e) {
  make = document.getElementById("vehicleMake").value;
  model = document.getElementById("vehicleModel").value;
  year = document.getElementById("vehicleYear").value;
  price = document.getElementById("vehiclePrice").value;

  let vehicle = {
    make,
    model,
    year,
    price,
  };

  if (localStorage.getItem("Vehicles") === null) {
    let vehicles = [];
    vehicles.push(vehicle);
    localStorage.setItem("Vehicles", JSON.stringify(vehicles));
  } else {
    let vehicles = JSON.parse(localStorage.getItem("Vehicles"));
    vehicles.push(vehicle);
    localStorage.setItem("Vehicles", JSON.stringify(vehicles));
  }

  leer();
  document.getElementById("formulario").reset();
  console.log(" Auto guardado correctamente ... ");
  e.preventDefault();
}

//Funcion "Leer"

function leer() {
  let vehicles = JSON.parse(localStorage.getItem("Vehicles"));
  document.getElementById("tbody").innerHTML = "";
  for (let i = 0; i < vehicles.length; i++) {
    let make = vehicles[i].make;
    let model = vehicles[i].model;
    let year = vehicles[i].year;
    let price = vehicles[i].price;

    document.getElementById("tbody").innerHTML += `<tr>
            <td>${make}</td>
            <td>${model}</td>
            <td>${year}</td>
            <td>${price}</td>
            <td><button onclick="eliminar('${make}')" class="btn
            btn-danger">Eliminar</button></td>
            <td><button onclick="editar('${make}')" class="btn
            btn-success">Editar</button></td>
        </tr>
        `;
  }
}

//Funcion "Editar"

function editar(make) {
  let vehicles = JSON.parse(localStorage.getItem("Vehicles"));
  for (let i = 0; i < vehicles.length; i++) {
    if (vehicles[i].make === make) {
      document.getElementById("body").innerHTML = `
                    <div class="row">
            <div class="col-md-5">
                <div class="card">
                    <div class="card-header">
                        <h2>Editando Auto ${make}</h2>
                    </div>
                    <div class="card-body">
                        <form>
                            <div class="form-group">
                                <input type="text" id="newVehicleMake" class="form-control my-3" placeholder="${vehicles[i].make}"/>
                            </div>
                            <div class="form-group">
                                <input type="text" id="newVehicleModel" class="form-control my-3" placeholder="${vehicles[i].model}"/>
                            </div>
                            <div class="form-group">
								<input type="text" id="newVehicleYear" class="form-control my-3" name="datepicker" placeholder="${vehicles[i].year}"/>
                            </div>
                            <div class="form-group">
                                <input type="number" id="newVehiclePrice" class="form-control my-3" placeholder="${vehicles[i].price}">
                            </div>
                        </form>
                        <button class = "btn btn-success" onclick="actualizar('${i}')">Actualizar</button>
                        <button class = "btn btn-primary" onclick="vistaPrincipal()">Cancelar</button>
                    </div>
                </div>
            `;
    }
  }
}

//Funcion Actualizar

function actualizar(i) {
  let vehicles = JSON.parse(localStorage.getItem("Vehicles"));
  vehicles[i].make = document.getElementById("newVehicleMake").value;
  vehicles[i].model = document.getElementById("newVehicleModel").value;
  vehicles[i].year = document.getElementById("newVehicleYear").value;
  vehicles[i].price = document.getElementById("newVehiclePrice").value;

  localStorage.setItem("Vehicles", JSON.stringify(vehicles));
  vistaPrincipal();
}

//Función Eliminar

function eliminar(make) {
  let vehicles = JSON.parse(localStorage.getItem("Vehicles"));
  for (let i = 0; i < vehicles.length; i++) {
    if (vehicles[i].make === make) {
      vehicles.splice(i, 1);
    }
  }
  localStorage.setItem("Vehicles", JSON.stringify(vehicles));
  leer();
}

//Funcion para mostrar la interfaz principal

function vistaPrincipal() {
  document.getElementById("body").innerHTML = ` <div class="row">
    <div class="col-md-5">
                <div class="card">
                    <div class="card-header">
                        <h2>Agregar nuevo vehículo</h2>
                    </div>
                    <div class="card-body">
                        <form id="formulario">

                <div class="form-group">
                  <input
                    type="text"
                    id="vehicleMake"
                    class="form-control my-3"
                    placeholder="Ingresar marca"
                  />
                </div>
                <div class="form-group">
                  <input
                    type="text"
                    id="vehicleModel"
                    class="form-control my-3"
                    placeholder="Ingresar Modelo"
                  />
                </div>
                <div class="form-group">
                  <input
                    type="text"
                    id="vehicleYear"
                    class="form-control my-3"
                    name="datepicker"
                    placeholder="Ingresar Año"
                  />
                </div>
                <div class="form-group">
                  <input
                    type="number"
                    id="vehiclePrice"
                    class="form-control my-3"
                    placeholder="Ingresar precio"
                  />
                </div>                        

                            <button type="submit" class="btn btn-primary">Agregar</button>
                        </form>

                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <table class="table caption-top bg-light">
                    <thead>
                        <tr>
                            <th scope="col">Marca</th>
                <th scope="col">Modelo</th>
                <th scope="col">Año</th>
                <th scope="col">Precio</th>
                        </tr>
                    </thead>
                    <tbody id="tbody">
                        <tr>
                                     <td>Audi</td>
                <td>Audi A5</td>
                <td>2021</td>
                <td>22,000.000</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>`;
  leer();
}

leer();
