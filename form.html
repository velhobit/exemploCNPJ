<!doctype html>
<html lang="pt-br">
  <head>
    <meta charset="utf-8">
    <title>Pesquisar CNPJ</title>
    <!--Importando Script Jquery-->
	<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
  </head>
<body>
	<!--Formulário-->
	<form id="post">
	  <label for="cnpj">CNPJ</label>
	  <input id="cnpj" required type="text">
	  <br/>
	  <label for="nome">Razão Social</label>
	  <input id="nome" type="text">
	  <br/>
	  <label for="fantasia">Nome Fantasia</label>
	  <input id="fantasia" type="text">
	  <br/>
	  <label for="atividade">Atividade Principal</label>
	  <input id="atividade" type="text">
	  <br/>
	  <label for="telefone">Telefone</label>
	  <input id="telefone" required type="text">
	  <br/>
	  <label for="email">E-mail</label>
	  <input id="email" type="text">
	  <br/>
	  <label for="cep">CEP</label>
	  <input id="cep" type="text">
	  <br/>
	  <label for="logradouro">Logradouro</label>
	  <input id="logradouro" type="text">
	  <br/>
	  <label for="numero">Número</label>
	  <input id="numero" type="text">
	  <br/>
	  <label for="complemento">Complemento</label>
	  <input id="complemento" type="text">
	  <br/>
	  <label for="bairro">Bairro</label>
	  <input id="bairro" type="text">
	  <br/>
	  <label for="uf">Estado</label>
	  <select id="uf">
	    <option value="AC">Acre</option>
	    <option value="AL">Alagoas</option>
	    <option value="AP">Amapá</option>
	    <option value="AM">Amazonas</option>
	    <option value="BA">Bahia</option>
	    <option value="CE">Ceará</option>
	    <option value="DF">Distrito Federal</option>
	    <option value="ES">Espírito Santo</option>
	    <option value="GO">Goiás</option>
	    <option value="MA">Maranhão</option>
	    <option value="MT">Mato Grosso</option>
	    <option value="MS">Mato Grosso do Sul</option>
	    <option value="MG">Minas Gerais</option>
	    <option value="PA">Pará</option>
	    <option value="PB">Paraíba</option>
	    <option value="PR">Paraná</option>
	    <option value="PE">Pernambuco</option>
	    <option value="PI">Piauí</option>
	    <option value="RJ">Rio de Janeiro</option>
	    <option value="RN">Rio Grande do Norte</option>
	    <option value="RS">Rio Grande do Sul</option>
	    <option value="RO">Rondônia</option>
	    <option value="RR">Roraima</option>
	    <option value="SC">Santa Catarina</option>
	    <option value="SP">São Paulo</option>
	    <option value="SE">Sergipe</option>
	    <option value="TO">Tocantins</option>
	  </select>
	</form>
	<script type="text/javascript">
		$("#cnpj").focusout(function(){
			//Início do Comando AJAX
			$.ajax({
				//O campo URL diz o caminho de onde virá os dados
				//É importante concatenar o valor digitado no CNPJ
				url: 'dados/cnpj.php?cnpj='+$("#cnpj").val(),
	//Atualização: caso use java, use cnpj.jsp, usando o outro exemplo.
				//Aqui você deve preencher o tipo de dados que será lido,
				//no caso, estamos lendo JSON.
				dataType: 'json',
				//SUCESS é referente a função que será executada caso
				//ele consiga ler a fonte de dados com sucesso.
				//O parâmetro dentro da função se refere ao nome da variável
				//que você vai dar para ler esse objeto.
				success: function(resposta){
					//Confere se houve erro e o imprime
					if(resposta.status == "ERROR"){
						alert(resposta.message + "\nPor favor, digite os dados manualmente.");
						$("#post #nome").focus().select();
						return false;
					}
					//Agora basta definir os valores que você deseja preencher
					//automaticamente nos campos acima.
					$("#post #nome").val(resposta.nome);
					$("#post #fantasia").val(resposta.fantasia);
					$("#post #atividade").val(resposta.atividade_principal[0].text + " (" + resposta.atividade_principal[0].code + ")");
					$("#post #telefone").val(resposta.telefone);
					$("#post #email").val(resposta.email);
					$("#post #logradouro").val(resposta.logradouro);
					$("#post #complemento").val(resposta.complemento);
					$("#post #bairro").val(resposta.bairro);
					$("#post #cidade").val(resposta.municipio);
					$("#post #uf").val(resposta.uf);
					$("#post #cep").val(resposta.cep);
					$("#post #numero").val(resposta.numero);
				}
			});
		});
	</script>
</body>
</html>