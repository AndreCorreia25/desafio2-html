# desafio2-html
Código sobre uma clinica medica 

<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Clínica Médica - Página Principal</title>
  <style>
/* Estilos CSS existentes */

/* Novo CSS */
header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

.header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo img {
  display: block;
  max-width: 200px;
  height: auto;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav ul li {
  margin-right: 10px;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color: #333;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.btn:hover {
  background-color: #555;
}


  </style>
</head>
<body>
    <header>
        <div class="header-container">
          <div class="logo">
            <img src="download.png" alt="Logo da Clínica Médica">
          </div>
          <nav>
            <ul>
              <li><a href="index.html" class="btn">Página Principal</a></li>
              <li><a href="clinica.html" class="btn">Sobre a Clínica</a></li>
              <li><a href="horaatend.html" class="btn">Horário de Atendimento</a></li>
              <li><a href="contato.html" class="btn">Contato</a></li>
            </ul>
          </nav>
          
        </div>
      </header>
      
  <main>
    <section>
      <h2>Clínica Médica</h2>
      <p>Bem-vindo à Clínica Médica, especializada em Clínica Geral, Pediatria, Psicologia e Oftalmologia.</p>
      <p>Nossa equipe de médicos altamente qualificados está pronta para oferecer cuidados médicos abrangentes para pacientes de todas as idades. Nosso objetivo é proporcionar um atendimento personalizado e de qualidade, buscando sempre a saúde e o bem-estar dos nossos pacientes.</p>
      <p>Agende uma consulta conosco e descubra como podemos ajudar você e sua família a manterem uma vida saudável.</p>
    </section>
  </main>

  <footer>
    <div class="footer-container">
      <div class="footer-left">
        <p>&copy; 2023 Nome da Clínica Médica</p>
      </div>
      <div class="footer-right">
        <p>Endereço da Clínica Médica</p>
        <p>Telefone: (00) 1234-5678</p>
      </div>
    </div>
  </footer>
  
</body>
</html>

