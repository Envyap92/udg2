<template>
    <div class="app">
      <!-- Menú de Navegación -->
      <nav class="navbar">
        <div class="logo" @click="toggleLogoSize">
          <img
            :style="{ 'transform': `scale(${logoScale})` }"
            src="/logo.png"
            alt="Logo"
            @click.stop
          />
        </div>
        <ul class="menu">
          <li><router-link to="/">Inicio</router-link></li>
          <li><router-link to="/nosotros">Nosotros</router-link></li>
          <li><router-link to="/propiedades">Propiedades</router-link></li>
          <li><router-link to="/proyectos">Proyectos</router-link></li>
          <li><router-link to="/promocion">Promoción</router-link></li>
          <li><router-link to="/contacto"></router-link></li>
          <li><router-link to="/blog">Blog</router-link></li>
        </ul>
  
        <div>
          <router-link to="/contacto">
            <button class="login-button">Iniciar Sesión</button>
          </router-link>
        </div>
  
  
        
        
      </nav>
  
      <!-- Contenido de la Página -->
      <main class="content">
        <!-- Sección de Inicio -->
        <!-- Sección de Inicio -->
  
        <!-- Sección de Inicio -->
  <section class="inicio-section">
    <!-- Banner -->
    
    <div class="banner">
      <img src="/logo.png" alt="banner" style="width: 200px; height: 200px;" />
    </div>
    
  
    <!-- Texto de Inicio -->
    <div class="inicio-text">
      <h1>Bienvenidos a HOUSE FINDER</h1>
      <p>Somos tu mejor opción para encontrar la casa o departamento de tus sueños. En HOUSE FINDER, nos comprometemos a proporcionarte las mejores opciones de vivienda, ya sea que estés buscando tu primer hogar, una propiedad de inversión o el lugar perfecto para tu familia. Navega a través de nuestras propiedades, conoce nuestros proyectos y descubre oportunidades de promoción exclusivas. ¡Estamos aquí para ayudarte a encontrar el lugar que siempre has deseado!</p>
      <button class="btn-learn">Aprende Más</button>
    </div>
  
    <!-- Tres Columnas en una Fila -->
    <!-- Tres Columnas en una Fila -->
  <div class="row">
    <!-- Columna 1 -->
    <div class="column">
      <img src="logo.png" alt="Imagen 1" style="width: 200px; height: 200px;"/>
      <h2>Encuentra tu Hogar Ideal</h2>
      <p>Explora una amplia gama de propiedades en las mejores ubicaciones. Tenemos opciones para todos los gustos y presupuestos.</p>
    </div>
  
    <!-- Columna 2 -->
    <div class="column">
      <img src="/logo.png" alt="Imagen 2" style="width: 200px; height: 200px;" />
      <h2>Proyectos Innovadores</h2>
      <p>Descubre nuestros proyectos de desarrollo inmobiliario que ofrecen comodidad y estilo de vida moderno.</p>
    </div>
  
    <!-- Columna 3 -->
    <div class="column">
      <img src="logo.png" alt="Imagen 3" style="width: 200px; height: 200px;" />
      <h2>Promociones Exclusivas</h2>
      <p>Aprovecha nuestras promociones especiales y descuentos en propiedades seleccionadas. ¡No te las pierdas!</p>
    </div>
  </div>
  
  </section>
  
  
  
        <!-- Resto del contenido de la página -->
        <!-- Puedes agregar más secciones y contenido aquí -->
      </main>
  
      <!-- Footer -->
      <!-- Footer -->
      <footer class="footer">
        <table>
          <tr>
            <td class="footer-cell">
              <strong style="color: #ba8c26;">JALISCO</strong><br>
              <span style="font-size: 12px;">
                Av. Acueducto 4851 Real Acueducto,<br>
                C.P. 45116. Zapopan, Jalisco.<br><br>
                T. 333 642 5065<br>
                W. 333 253 0684<br>
                infojalisco@activoinmobiliario.mx<br><br>
                L-V de 9:30 a 19:30 h<br>
                S y D de 9:30 a 14:00 h
              </span>
            </td>
            <td class="footer-cell">
              <strong style="color: #ba8c26;">GUANAJUATO</strong><br>
              <span style="font-size: 12px;">
                Paseo El Molino 302, El Molino Residencial,<br>
                C.P. 37138, León, Guanajuato, México.<br><br>
                T. 477 781 1119<br>
                W. 477 852 4437<br>
                infoleon@activoinmobiliario.mx<br><br>
                L-V de 9:00 a 20:00 h<br>
                S de 9:00 a 19:00 h<br>
                D y festivos de 11:00 a 19:00 h
              </span>
            </td>
            <td class="footer-cell">
              <strong style="color: #ba8c26;">QUERÉTARO</strong><br>
              <span style="font-size: 12px;">
                Av el campanario 100 fracc. Hacienda el Campanario,<br>
                C.P. 76146, Querétaro, Querétaro, México.<br><br>
                T. 442 192 7722<br>
                W. 442 503 0960<br>
                infoqueretaro@activoinmobiliario.mx<br><br>
                L-V de 9:00 a 20:00 h<br>
                S de 9:00 a 19:00 h<br>
                D y festivos de 11:00 a 19:00 h
              </span>
            </td>
            <td class="footer-cell">
              <strong style="color: #ba8c26;">QUINTANA ROO</strong><br>
              <span style="font-size: 12px;">
                Carretera Federal Cancun – Chetumal Km 299<br>
                C.P 77500 Playa del Carmen, Q.R<br><br>
                T. 9841005901<br>
                W. 9841005901<br>
                infoquintanaroo@activoinmobiliario.mx<br><br>
                L-V de 9:00 a 18:00 h<br>
                S, D y festivos de 10:00 a 16:00 h
              </span>
            </td>
            <td class="footer-cell">
              <strong style="color: #ba8c26;">VERACRUZ</strong><br>
              <span style="font-size: 12px;">
                Km. 4.5 Carretera Federal, Antón Lizardo,<br>
                95264 Boca del Río, Ver.<br><br>
                T. 229 179 4444<br>
                W. 229 168 2680<br>
                infoveracruz@activoinmobiliario.mx<br><br>
                L-V de 9:00 a 19:00 h<br>
                S de 10:00 a 18:00 h<br>
                D y festivos de 11:00 a 18:00 h
              </span>
            </td>
            <td class="footer-cell">
              <strong style="color: #ba8c26;">CHIHUAHUA</strong><br>
              <span style="font-size: 12px;">
                Edificio Metroloft, Oficina 209, Segundo piso,<br>
                Calle Citadela, número 5900, Distrito Uno, colonia El Saucito.<br><br>
                T. 567 179 56742<br>
                W. 229 168 2680<br>
                infoveracruz@activoinmobiliario.mx<br><br>
                L-V de 9:00 a 19:00 h<br>
                S de 10:00 a 18:00 h<br>
                D y festivos de 11:00 a 18:00 h
              </span>
            </td>
          </tr>
        </table>
        <p style="font-size: 12px;">&copy; 2023 House Finder. Todos los derechos reservados.</p>
      </footer>
    </div>
  </template>
  
  
  <script>
  export default {
    name: 'App',
    data() {
      return {
        logoScale: 1, // Escala inicial del logo
      };
    },
    methods: {
      toggleLogoSize() {
        // Cambia la escala del logo al 150% cuando se hace clic
        this.logoScale = this.logoScale === 1 ? 1.5 : 1;
      },
    },
  };
  </script>
  
  <style scoped>
  
  
  /* Estilos para el esqueleto de la página */
  .app {
    font-family: 'Roboto', sans-serif;
    text-align: center;
  }
  
  /* Estilos para el menú de navegación */
  .navbar {
    background-color: #ffffff; /* Azul indigo */
    color: #fff; /* Texto blanco */
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: px 0;
  }
  
  /* Estilos para el logo */
  .logo img {
    max-height: 150px; /* Tamaño inicial del logo */
    transition: max-height 0.3s ease; /* Transición suave de tamaño */
    cursor: pointer; /* Cambia el cursor al hacer clic */
  }
  
  /* Estilos para el menú */
  .menu {
    list-style: none;
    display: flex;
    gap: 20px;
    margin-left: 10px;
  }
  
  .menu li a {
    text-decoration: none;
    color: #1f1f1f; /* Texto blanco */
    transition: color 0.3s ease;
  }
  
  .menu li a:hover {
    color: #ba8c26; /* Dorado en hover */
  }
  
  /* Estilos para el botón de inicio de sesión */
  .login-button {
    background-color: #caa24c; /* Dorado */
    color: #292929; /* Texto negro */
    border: none;
    padding: 10px 20px;
    border-radius: 20px;
    cursor: pointer;
    transition: background-color 0.3s ease, color 0.3s ease;
    margin-right: 100px; /* Añadido margen derecho */
  }
  
  .login-button:hover {
    background-color: #12407c; /* Negro en hover */
    color: #fff; /* Texto blanco en hover */
  }
  
  /* Estilos para la sección de inicio */
  .inicio-section {
    /* Personaliza los estilos de la sección de inicio aquí */
  }
  
  /* Estilos para el banner */
  .banner {
    /* Personaliza los estilos del banner aquí */
  }
  
  /* Estilos para el texto de inicio */
  .inicio-text {
    /* Personaliza los estilos del texto de inicio aquí */
  }
  
  /* Estilos para el botón "Aprende Más" */
  .btn-learn-more {
    /* Personaliza los estilos del botón "Aprende Más" aquí */
  }
  
  /* Estilos para la fila de columnas */
  .row {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  
  /* Estilos para cada columna */
  .column {
    flex-basis: calc(33.33% - 20px); /* Ancho de cada columna */
    margin-right: 20px; /* Espacio entre columnas */
  }
  
  /* Estilos para la última columna (para eliminar el margen derecho) */
  .column:last-child {
    margin-right: 0;
  }
  
  
  .btn-learn {
    background-color: #caa24c; /* Dorado */
    color: #292929; /* Texto negro */
    border: none;
    padding: 10px 20px;
    border-radius: 20px;
    cursor: pointer;
    transition: background-color 0.3s ease, color 0.3s ease;
    margin-right: 100px; /* Añadido margen derecho */
  }
  
  .btn-learn:hover {
    background-color: #12407c; /* Negro en hover */
    color: #fff; /* Texto blanco en hover */
  }
  
  </style>
  