<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela</title>  
</head>
<style>
    thead{
        font-family: Arial, Helvetica, sans-serif;
    }
    tbody{
        border-collapse: collapse;
    }
    td,th{
        border: 1px solid gray;
        padding: 8px;  
    }
    td.id,th{
        background-color: gray;
        color: white;
        font-weight:1.2em;
        text-align: left;
           
    }
</style>

<thead>

<body>
    <tbody>
    <table>
        <tr>
            <th class="id" scope="colgroup">Area</th>
            <th class="id" scope="colgroup">Disciplinas</th>
            <th colspan="2" class="id" scope="rowgroup">Notas</th>
            <th rowspan="2" class="id" scope="row">Média</th>
        </tr>
        <tr>
        <th rowspan="4" scope="colgroup">Exatas</th> 
                
                <td>Matemática</td>
                <td class="id">Nota1</td>
                <td class="id">Nota2</td>
               
            </tr> 
        <tr>
            
            <td>Fisica</td>
            <td>0.0</td>
            <td>0.0</td>
            <td>0.0</td>
        <tr>
            
            <td>Química</td>
            <td>0.0</td>
            <td>0.0</td>
            <td>0.0</td>
        
        </tr>
            
            <td>Biologia</td>
            <td>0.0</td>
            <td>0.0</td>
            <td>0.0</td>
        </tr>
        <tr>
            <th scope="colgroup" class="id" colspan="4">Média de Exatas</th>
           
            <td class="id">0.0</td>
        </tr>
        <tr>
            <th scope="colgroup" rowspan="2">Humanas</th>
            <td>Historia</td>
            <td>0.0</td>
            <td>0.0</td>
            <td>0.0</td>
        </tr>
        <tr>
            <td>Geografia</td>
            <td>0.0</td>
            <td>0.0</td>
            <td>0.0</td>
        </tr>
        <tr>
            <th scope="col" class="id"  colspan="4">Media de humanas</th>
            <td class="id">0.0</td>
        </tr>


        
       
       
    </table>
    </tbody>
</thead>
</body>


</html>
 
