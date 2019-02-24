# 
<i>Contém no repositório um projeto simples usando JQuery para consumir resultados em JSON de uma WebService de consultas de endereço via CEP.</i>

´´´ JavaScript

        $.getJSON(url,function(json){
            $("#ilogradouro").val(json.logradouro);
            $("#ibairro").val(json.bairro);
            $("#icidade").val(json.localidade);
            $("#iestado").val(json.uf);
            $("#icomplemento").val(json.complemento); 
        })
    });
});
´´´
**WebService Utilizada**: https://viacep.com.br/


