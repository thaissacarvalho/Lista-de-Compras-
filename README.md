#Projeto Lista de Compras - Utilizado no Curso Objetos no JavaScript - Escola Front-End Alura

Neste arquivo encontram-se modelos de códigos que serão utilizados no decorrer do curso e suas abordagens. 

/---------------------------------------------------------------------------------------------------------------/

Código modelo da li "Comprados":

    <li class="item-compra is-flex is-justify-content-space-between" data-value="">
        <div>
            <input type="checkbox" checked class="is-clickable" />  
            <span class="itens-comprados is-size-5"></span>
        </div>
        <div>
            <i class="fa-solid fa-trash is-clickable deletar"></i>
        </div>
    </li>

Código modelo da li "Lista de compras": 

    <li class="item-compra is-flex is-justify-content-space-between" data-value="">
        <div>
            <input type="checkbox" class="is-clickable" />
            <input type="text" class="is-size-5" value=""></input>
        </div>
        <div>
            <i class="fa-solid fa-trash is-clickable deletar"></i>
        </div>
    </li>

Input com código refatorado:

    <div>
        <input type="checkbox" checked class="is-clickable" />  
        <span class="itens-comprados is-size-5">${elemento.valor}</span>
    </div>

Ícones de edição:

    <i class="fa-regular fa-floppy-disk is-clickable"></i><i class="fa-regular is-clickable fa-pen-to-square editar"></i>

/---------------------------------------------------------------------------------------------------------------/

A única parte que fiz parte do desenvolvimento foi a parte do arquivo "main.js" com o professor Luan Alves da Alura.

No curso é falado sobre Object, setItem, getItem, splice, push e localStorage.

Finalizado em 28/04/2023.