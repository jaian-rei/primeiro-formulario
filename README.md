<form action="/pagina-processa-dados-do-form" method="post">
<fielset
<legend>dados gerais</legend>
<label form="name">nome:</label>
input type="text" minlength="3" id="nome" />

label for="data_nascimento">data de nascimento:</label>
input type="text" id "data_nascimento"/>

<label for="cpf">cpf:</label>
<input type="cpf" minlength="11" id="cpf" />
</fielset>
<fielset>
<legend>endereço</legend>

<label for="tipo_endereço">tipo:</label>
<select id="tipo_endereço">
<option value="">selecione</option><option value="">rua</o]
<option value="">rua</option>
<option value="">estrada</option>
<option value="">rodovia</option>
<option value="">outros</option>

</select>

<label for "logradouro_endereço">logradouro:</label>
<input type="text" id="logradouro_endereço" />

<label for="numero_endereço">número:</label>
<input type="text" id="número_endereço" />

<label for="complemento_endereço">complemento:</label>
<input type="text" id="complemento_endereço" />
</fielset>
<legend>fale conosco</legend>

<label for="msg">mensagem:</label>
<testarea type="text" id="msg"></testarea>
</fielset>
