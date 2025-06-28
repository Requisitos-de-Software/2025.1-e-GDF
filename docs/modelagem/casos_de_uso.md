# Casos de Uso

## O que são Casos de Uso

Casos de uso são uma técnica de modelagem usada para descrever os **requisitos funcionais** de um sistema, focando nas **interações entre usuários (atores) e o sistema** para atingir determinados objetivos.

## Definição
Um **caso de uso** representa uma sequência de interações entre um ator e o sistema que resulta em um **resultado observável e de valor** para o ator.

## Objetivo
O principal objetivo dos casos de uso é **documentar como o sistema deve se comportar** em resposta às ações dos usuários, servindo como ponte entre analistas, desenvolvedores e clientes.

## Características
- São representados por **diagramas de casos de uso**, utilizando a notação UML (Unified Modeling Language).
- Os **atores** podem ser pessoas, sistemas externos ou dispositivos que interagem com o sistema.
- Cada caso de uso descreve um **fluxo de eventos**, podendo incluir:
  - **Fluxo principal** 
  - **Fluxos alternativos**
  - **Fluxos de exceção**

## Notação
- Usar **verbos no infinitivo** para nomear os casos de uso, pois eles representam **ações**.
- Casos de uso são representados por **elipses**, e os atores por **figuras humanas** (para pessoas).

## Tipos de Relacionamento
- `include`: Indica que um caso de uso **sempre inclui** outro.
- `extend`: Indica que um caso de uso **pode opcionalmente estender** outro.
- `generalization`: Herança entre casos de uso ou entre atores.

# Componentes e Símbolos de um Diagrama de Casos de Uso

| **Componente** | **Descrição** | **Representação** | **Observações** |
|----------------|---------------|--------------------|------------------|
| **Ator** | Representa um usuário ou sistema externo que interage com o sistema. |  <p> boneco de palito </p>   <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/ajuste-simples_imagens/docs/assets/modelagem/casos_de_uso/ator.png" style="height:100px;width:100px"/>| Pode ser uma pessoa, sistema, dispositivo, etc. |
| **Sistema** | Define o escopo do sistema e contém os casos de uso. | <p> Retângulo </p> <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/ajuste-simples_imagens/docs/assets/modelagem/casos_de_uso/retangulo.png" style="height:100px;width:100px"/> | Casos de uso fora do retângulo estão fora do escopo. |
| **Caso de Uso** | Representa uma funcionalidade ou ação do sistema. | <p> Elipse </p>   <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/ajuste-simples_imagens/docs/assets/modelagem/casos_de_uso/caso-De-uso.png" style="height:100px;width:100px"/> | Ex: `Realizar login` |
| **Comunicação** | Relação entre ator e caso de uso. | <p> Linha sólida </p>   <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/ajuste-simples_imagens/docs/assets/modelagem/casos_de_uso/linha-solida.png" style="height:100px;width:100px"/> | Indica que o ator executa ou interage com a funcionalidade. |
| **Inclusão** (`<<include>>`) | Um caso de uso inclui outro obrigatoriamente. | <p> Linha tracejada com seta e nome `<<include>>`. </p>   <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/ajuste-simples_imagens/docs/assets/modelagem/casos_de_uso/linha-tracejada.png" style="height:100px;width:100px"/>  | O caso incluído **sempre** será executado. |
| **Extensão** (`<<extend>>`) | Um caso de uso pode adicionar comportamento opcional a outro. | <p> Linha tracejada com seta apontada para o caso base e nome `<<extend>>`. </p>   <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/ajuste-simples_imagens/docs/assets/modelagem/casos_de_uso/extensao.png" style="height:100px;width:100px"/>  | O caso estendido **pode ou não** ser executado. |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

## Metodologia

Para o levantamento e modelagem dos requisitos do sistema, foi adotada uma abordagem baseada na **Engenharia de Requisitos**, com foco na identificação e documentação dos **requisitos funcionais** por meio de **Casos de Uso**.

A modelagem seguiu os princípios da UML (Unified Modeling Language), utilizando o **Diagrama de Casos de Uso** como ferramenta principal para representar as interações entre os usuários (atores) e o sistema.
A ferramenta utilizada para a criação do diagrama foi o **[Drawio](https://www.drawio.com/)**

## Diagrama de Casos de Uso 

<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/ajuste-diagrama/docs/assets/modelagem/casos_de_uso/diagrama.drawio.png"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/ajuste-diagrama/docs/assets/modelagem/casos_de_uso/diagrama.drawio.png" alt="diagrama-casos-de-uso-2" border="0"></a>


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>


<font size="3"><p style="text-align: center"> Disponível de forma online em PDF:  [Clique aqui](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Diagrama%20de%20Casos%20de%20Uso.drawio&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22P%C3%A1gina-1%22%20id%3D%2234NzMq-ass0gtIXJ2DlH%22%3E7V1bV9tItv41rDXzAEtVpeujA0k6s9I5nNCT6T5vwhagjG05skxI%2F%2FpTJatka6uMC1lVKkH1QwdkY4T2pfb37dsZuVw8fczj1cPv2SyZn2Fn9nRGrs4wJn4Q0X%2FYlV%2FbKzh0yPbKfZ7OttfQ7sJN%2BndSXXSqq5t0lqwbbyyybF6kq%2BbFabZcJtOicS3O8%2Bxn82132bz5W1fxfdK6cDON5%2B2r%2F0lnxcP2aoiD3fXfkvT%2Bgf9m5Fd%2F8SLmb67%2BkvVDPMt%2B7l0i78%2FIZZ5lxfarxdNlMmdPjz%2BX7c99OPBqfWN5sixkfuAaFcVl%2FufV6o8fm0%2B%2F%2FeY%2FPa0%2Fn%2BPtpzzG8031B59hf04%2F790sfaRf3rMv%2BaW7jP4m%2BodwIfk%2FNuzm35Hdl%2FBHbnN4hd7g9nNalwW%2F0d6EvQl7E%2FYm7E2M%2FSaEnzii%2B7c3YW%2FC3oS9CXsT9ibsTdibsDdhb8LehL0JexP2Jt7kTRwH9CXpXfziTHqebZazhJHRDn3550NaJDereMpe%2FZnHK3rtoVjM6Xeo%2Ful9crviux%2BTvEie9i5VZPfHJFskRf6LvqV69Rw7FfNe5R7OSVhd%2BLlj8iOeaHjYY%2FG9%2BkfjKn1wX3%2F8jmGnX1Qk%2BwsId3KQcOdSrZ8YlyV74Xwr7Al9AwpXT9unDmT9NYnn6d8xlYvzObtPl%2FTfm3Sxmqd36TSeZQcFD%2BRE%2F4h0tU70yAgRICPstWWEPIGMQlUSCtRJaDJN1utSQJ%2BWRZLfsSfbEFI8DiEJ7Ki2GC0yilRa0TS5TZiMvmRFKZWzS3I2Cdj%2F33nJmr7wLl4nVFbsy2RRWtu0tLzdGydkHOYWCQSJdQqSe18VkrzMluvNvCjt7ZI%2BtDwuc9PM5Cb3yXIWL%2BjFrJQis8Ikf0y3EmTXjBSe1xCe6wikR3RKjyCF0ktn8eyFtrR%2BiFfsy81iPpkWWU7fw54vteH55%2Fg2mV9n67RIsyV9y21WFNli7w2TeXrPXigyILpsU8zTZXJZFxg4PckzAMaIItHZJ%2FKrKFIm0cMFAbf8sd%2Bk6yJZxMxuzj9efdgTzu1BydBnUjQfa1w972nCjkKBIBbpbDY%2FZFrNYJIpRVU6gt1%2BpINcGDwGktbmK5ONp87avlFxzLaeMk9myXKaxqmRXtD1YMDoC%2BTiavWCvjq50H%2FjBXuK8%2FZ36XI636R5fbH5A8%2BDPSDBPRlBM6wd5Zx50Hfx9L%2F3pfFdZnPmYK%2BW2ZJJnp6nE1ZuRa9kq2S5vfIhZU%2ByNFEaLj2U9opa1ntQK9bZJp9Wd%2Fj%2B%2F5a%2FfmR%2F%2Fmtz8%2F3hg%2Fuf74t%2FZx84mKJH%2FH1SSFhOMmsUex1UMucCIRIBPWu7Zq55eTKPi%2FSxWTEmUrPqF15naakWXOFxU6XdAGjq9jlUP7VT1tYHeaj5QcQDH7R9UK0PooKLf%2B29bcXesBb%2FKv6e7O5unTQ%2BpbSd%2Bll2NydPIUTeHV0fs8eLksJ4fYFFGEkcXZEorICK15uL9FwdMi1D%2B0Oo7Q0IGov4LZGclYUonsIQBciZPo75Kbh7XJIOm5IWxDyRJxA0PAD6E7TSmMcBsv6aTOl9U8T%2BBiQNggEUCpy3ZlDoKaREW1adQyFvX7jKphvO17xGsQNYg9zhxc6dTEPsEPrtwv4KCOw9rGaYnzylxZ%2FVK%2Bzrv9j1CwL%2Bq168etr7qatfe99cJ3lK%2Fz5GGWyvLenf%2Buf%2BN9sP9vi3u48qv%2Ft1TGj7qONZ1us47DiTQx17IhZlOrx%2BYMY5AZQGPR06Ao1zHEF1lYQafYEEX8Q89q2b3vPKeEDxRBr9jB6W30GlPkE5PUnl9MzSzlaE43bUzQiwqh70j6o1UwR1rNcUek0xqRMYpZg7gpGjLIxJR7cZNhM4qOaPdemmCJ5Z3ZQ%2F0SOzVBMBp4kir6NqIlArgxCky1WrpghQnqCaHXVIkUprUE3O%2FZqimzXpWEeb0NlJu02YJyWQp1Stm6JyE6ub8kc6NsxvYkiyBKSvIx3BuFWxbnJTsLrZUTddbJZuwiQewj5pPEivq6ZCL4o1a2rPkP3Naaovm8XWdcLDmDFwunpR5AA3Guh2o6Kks1VOeeX0QrOUE6J2FEB31105W9yUauXsmVJ6c8oZmEYpQWwUQvq8s3LuJmfpUk4L3E9TztCwALTFdzrdPSeIZTHRTHgGoVXO05TTcM%2FZTn%2B%2FwHOCj3JhWZRq5bS00mnKGZnmOaFyup0T7K1j3deM1jlbYJWza8xpGh8P3V2rIaI7IIo0E%2FKhKirpwnHcpoKSAA2jon3XhUg7VcNO%2FJbeks4nfhRdRLv%2FfN63s6ue1qzF2LrYk1QVOWbVMJ1jAgOAztDpiK5GsAZFta5afvRUXTWMICUYxgMnICn3OWUlLQKhP2Ut%2Fvr61x15%2F2kef38IZ5tvi19fLs%2B5blpl7VhLYlgIAFOiUdhLRhSBIuZA3fkvVlPrU09M3RvmUltlJT7PinVgTvEFAFmeuqyTUD25GPa1kT7om%2BrbLC8esvtsGc%2Ff764Cldy953PGOmlKHfueFMWvalpDvCmypk5zbdxV3%2F%2B194pY%2FQ6q2lHFOFHiHqj%2BwUHXGrfjn9SftMXxicAXqWnxmmwKKqdGh67BzXytFi6BorX1ijc1wE7suiFzzyOFqho3xaV46uT83KyK91QFqGPIRz%2Bsoj5la1roZacs%2F3rvp474NeDEFE%2FKeFaf9c7FCGBLUFfnCqFO64NMm4vxnAgVzbzbrJK8nP9zkywfVI0hPMmZoiAAIdGBYZECf9rH7B9xCCoQygkhvJFtiC91QNJ9iYcDkaFCeOhyAl4d%2FFKXE3IanX%2BQuqoccd5%2BmGP%2BtYyk6tMQ5drWejGyQNLGIoNO%2BTrU5Ydz18ZfDMZj%2Bi64l1Gc8gon205WebKmOlUe81fUoNYckn2JH5N7LeNrT4oAIA8omkOsbFb0AVZfobi%2Bb9ZbWV3nyR09k5lgJmwy405uJ826GlJ0SDB5uPYoekSnkPH4RuMoJpdSeEm%2BSNfrvfHRpeh0zow%2BTXIOuQianlU0mkav7CyL0U98MxAbwZ2BXL%2B9IYEKgVbQOVBBEGSMkY5ACvmINwExek3XqTDd5yZgHIfxJk3YhYW5QdfSR%2BIBHxCOEWMgHWNgxsZaPRskHp%2Bm5YnVXQ9t5cNmR6crVR75IOvsOiCFrToPKZo1aXXzlCBqO3x5MEoVdom3GhRfMKMIlkSEepUTK4T7VZacAUS2HOo%2Bj2flbpp%2F3JQY8d2EwUZ628772aaVO2fX%2F8jj5XqVUaj3z1eZTI9AFq%2BmFPZz6QI97mXatVgdFMJQGkQW24Qc2FVEJUz%2FfxlTFcny1MhMnQdM3uN2ux%2FaBToJA2GpXW%2BGu5zm2bLavHdVme1M106pkyTlAkwr2hSARCPk1UlKlFG11M5Lt6n0EmFw%2FyY5e84QsOeGzfLzEFafS%2FM0wI2FxJWKNswCe1jhSgbL00gUfF0wTLWPPvwj8ONgMXUvBI4INjxzZhpi1Agg3KjrwBTXBRjCkazMMMyqe5668nphsugQewbcDQWToYK7XSnKqDWVzdUMki2DI6uagqpcA1XTh9OqOpfoIEKaZXE4goNXVSunwvoaRtvk8T2LeZxpxhZDT9ZrxurQ6%2FSbb2lebMoVxFsI%2Fy3720RIeI4QqKMSLJtCIqJFGSbkZLYS9J7N02laVKXPDbjOqZZsES9n9SIiQ8Xmggaiel7MYEhe5XLo6zybJut1PCL5wGbT4eWD1cnnTTAtY20FkgaAJlXfwGZt5IQdhw23cqWSw4vMAoDElt%2B88vKbZ%2BPX41uUTKq%2FQXCDh9MV3WKfND8JSaaADbNehVkOwe7U5UMyTcsMYocoaVRJYthxHciuRO5j9bVY1LbYqu%2FAhAxa0BJCZxbBAgNpOoSigMZH4QDu71JMhxBLI8sqp%2BxQmmGV028pZ9dECYJl6tq5OqJw7fSkpg%2F%2B2BSsjiblhVc5e%2FxmVmucI1ACFQ7eRUUUNho3qLlNWdlGv5rM6EU2UshECbmAKg%2BxoPJJNPBFnYB0NZRex%2Bs1Cy%2Fj3dcGygf090euwIC0VqbxG7AsnGYWrs%2FYIJSNDYJntVMzKD%2B6jVh62AWs8PbBRMZRYHJXYb7CMmrGMmpEdmgGMYkOby1z7Gq7LS9AolEaL1ZnvJfZ8i6931TV%2BAw4pLfpPJ3FWyYtXW%2FMDEbP27SrqLxbayrfVUl8xvPHKiNcCQzOxagGUAIRmic5mMxHjmjQmd44VWEZ8WQ1r4ZlHJZcwupp%2FkgWK4YxviZmWhyEF7tt0MPJTcTwWXwxKnzBnabkLmtDQhQUwcgC5likhyPDYAduKhhHiKKQzrT4Yih8cdwmPVkrN8l4j5qc%2FJIF2LMN1zWMw3gV8twTKqcy%2Bvk9K8sY36%2Bnm9xI%2BrSNKLBoBJ9WROEpRBTXeXafx4st8GNSAm33bJY9dXrsW1ROtDdQZq2YtKb5BotJPS1Y4o9tEYy51tSSDBkcLXgWLfQVpFxEQdQMVFwSHgtVFBcxeNJAIjQoFsHIbdqJDxuxu5b%2BeqMEEp4FEsMCiQvHAWDCD5%2BFE%2F21dD8bnB4160NTyoxIYbTWr3VOYYSjHKjpqZ3ZX37Qbc6vfKzWfXxlQix5VpKnZdcbo8gvs8Uqzx7jZbEbJ737WRODqfOaaq0n14mKo%2FRCE4W1N0xCMfWc8wfeBMcFZqJ0YF0UcgdPaHAvpmR4V5Yv4mrOfjbd8Mp7%2BrwYIvm0YHVTa4NnfrfE5Q0vroGqM14fMhkuj8H94fE4xSj44eOmMfh8t8%2FLxx%2FAQQqjxB%2F8eVj8MdhEqQg38Ic%2FJPrwZNGHb9KUOLh2CAVdMxw4aN40CoMxZjh8UUMxjEFsK9CBY0w8ePlAue8wrUCYdAbYJGwegdjFeluBfFGSxyrnM7DGcOUMAqicnaeCYw%2FMlAp9zcqpMJ3VqD39NEuzhZFJxnZiWDjfRi9iVJjLuqLGOy0aQtnmgmMWSy4SY2kYwJT6w%2BN6lU2eu1xwHs82xq9aa5X9BqKEsNb9xv5Ai2TfPO3SZUiUYqDHHepxoGdSmgn7zXHgKAo6Zo9bGYbW4IdxAD2FWQlL30jRNxTONKw6GtauZVez%2B0a1r0J463Se8%2B81PQSFFHiEds3DNiWFkEm%2BZjMXqiUn9Nu7lN0QyxULthObF1q108PR4AAlUJjS%2BprMkrt0Wc4iHoWAWinHUARNfHyhM%2Frl45nUVH1vansSjGxbsKVP5iMWWFEXiaSmdaxtMNBgTItYzEMs3MMejWwCk1JTELGwNtJukQ3gE7Azynwzx2sWsLypxjl%2B%2BB63cpOMly%2BE3pkcmE%2FbGZXUdSjjMl47%2FvSEw0qcufPF%2Bq4pcwdmEO42G7w8c%2BfAbTCax58GdvyprHLiUShnq%2BbB6zwXCfJLxHE0K6fCzBhFmMktwyrO52RxmydFwiv%2FJ3Man5hJEZwjsLuPzcVpH%2BR6ORyF%2BbFG7v9DnvzY7DgcThXsic88gblhTdfU4ZBoApWrldNRmP74Rh3wXZVyvs7jv8t%2BmmtGCyyNFRFwmHUzVSPlrNOk%2BAdbAqcr3ht2v1AgWw8cmJROgu2ImHRNJ8Eh3ZiMsh0xVJidsKyLVJrYBVX%2BnvusDasmU2UHpQYmDUqFdf7Y7VoFTVrAFx6B47BrrM6uPyZUrWh0yuKfyT3LYJWtjywKumRaXia8ZqYuV4CaQkS5LK0NxKHCXNb%2BdoWvSbyTlonCESAJIhpjpHX3RagwL3FDj8E8W1b54aut0VTjaw0XlQ%2FdpBtctDEFdrSKSmGJvsUU6jEFd4RHY4%2Ft6WZI7IF9kAxyYWdKxw0L1KZGGXoMNF3srUOKPg0Ryxqia5AhtmpFva7dZgSBlJWPxrh%2FNFSYW2jQ1l%2ByomREW%2FPcVxl7%2BTIuknu2fs3ESKadbxi%2BXSpUuW8tndfobU8w26n7VJypwY1tfgsf%2BEiE3nRmGkKFmYb96lFBfe8WKbSNz9QyUgi9Rd2jehEDL2qwiEEjYjBgRlEom70ITcpeEAS9X9gRacA%2BiV1JxagCnMhmL3qCGheOD6zRj45WI%2B1yGAHIYYQvLwhXXdsUyiY2QqMSGzAdEXRNWBInbH5S6IG7GYfJY3UmD6ZtsuCq3jZWT3g0NK0BHXo0%2BFzUSGVag4ulXBj2ZfPI%2FjVPLLDdDUciuKI1nREpTGc8PxB1z7rMTWsQ%2FwI3gywi2u5G%2FbDWFsXIZjbeJE6JZDMi22PRkKClHkHXcnsvxikwzRiOchhHZFMir7C37bj1YlnrNSqN0golu3ZXwM5UCkFGab0qh5dt6AFbVMXkjyUR%2FzF7vCi3MBgXHZ0jAgTqimIjvQyuypV9%2B8LZprLY0IblQzJNeXD7IZ6amddyoayIoCkDY52yQo5Cuv1bzDZ9Mxld5smsTHGla6PNCeZDiC%2FKhyC9ErILGN4m0JBNiEQmJURgxRRxIDyQ3y4FP2mUoQpy8DD2a5FGnQvxwobpB4POxolksx7V2WyIYUPcT1DXtAfcBklQJNfgbZphK2TTJ1NGzS4fqql%2Fy1mzyuT9bDOlUW62LAMq8%2BKo1lhyEvKS3AEDKYU8uw2kzA2k6mEFEh6XGORxiQfgYj2s48WhVASsEcNevJF4XIU5l91kjoOls7Pt1NXteAHznK4L9SUQJZy1zoREjkKavdmqRQ%2FMs%2F2Bnu%2FX02weG8oyBKBolkTIb4sq1JvRRI7db20YUvHxoFClDnElTs4D46fMwCo46HhykhZlO8pJnshRyMl%2FTVZZXlQV8dntnPpfdlpuUye%2FxysjufgWQnHrmGhAMl5l48IyedoOtMrKLEnM%2FlcuITez7AfUablIIB69LUCIw1U1ExzoMTTday3ZGpKRovFbFVmucGSDZunYPMmA8J7GLiGA%2BK6DjwU%2BigvMa4cqEb%2BYtPkadpWQ7tM0QeUIcSFrO474BeFhjNtCkxqahKBkK%2BBQZSBoIpserY5tQ0wbdo8Qt2t%2BFIfN7hHij7IQkz58hUHvNFmvt5teNgykJDzw%2Ffd6O9MV5amR4W%2Bre8T1ojZDpLeuq96GoWh4QVE1KkyKanCriYJxfRD5eqJxWFq7ehBSSItfJ%2Bsfm3RrQx8m%2F2ukSFp0quuLph1rnUGA0EAF5haODJxt5F5SIjAxKduIeYhdhxNwwI405gC9JsSHvSYjCUxsOqS3VnYnaBokcY9yA3vjeJvIw49ejjyUMw1IOlOCTFrS3IIjPjwRpeEIAf4j4GM6R2b1Shevw42TNSyRs%2Bf1Q7xiX24W88m0YHZa2%2FVnZsbX2Tot0qxh39DwiwyEYNmmmKfLhEbgy2RaNGzjpLgsdBGMy7xQEJeJQAyCabYeAzNRkgWGr3b30AtDmQP0qZ7tQx6MOHDX2tQIFp0HWO%2FyodohW%2FU8rp7SdX3Dqmcd%2F9aHbOfNbXUJXK2fSLd%2BitJsJ%2Bhnr33EIg3VwFALF7IR2X2bB3GgHu08J8DnoaBzDAgU3XP5iCdt2ok1RW8fP9280qAN8M7Ccf%2BaQzastHIfxuT%2FM83y5lTP1yhnWP7k8NEIQ8rZ7qyVjn0c2dNl%2BwyHOl1gHRdxu5ZiRj6cdCDZNtbf4SKiBqx6nlZ4gw8MWtGEHFuVwp17bJxWu06gWz8Vlo82jsld%2B%2BH8dR6OsGpK1L2o%2B3AklhiQ9j6%2BtPc5MFlWEzHQqs7zAV6S333ZavGT3FTTm%2FchPRMDr1k%2FpYmrYfXThbyqF3TUz9DFQD0lc8L9qacuZqDEkOKhVG%2FktBQ2A%2Bg%2BLUWUgfVGp8wZqkxoMGcER0pQbNnNGQWgewVHkkXx%2FTkjpcOD92nKF41aG5fbac1qE3WI6XY7oqo%2F63aemzwo4XcOVMxooghgiYxDugbpDsiP4FCym7g%2Fx6O0pg1GQZN8Ef%2BdLF82XH5kTiiE%2B88igRviS4EaXggSoT16IbU1TJPVqhxC9UQdw1J%2BFsrIBHto3Nm%2BWEWHi0Kx2sol2ZhWuhqTHBieqSmmhZUhDuoa08JNxaHumJajQKudR7VTuqyODFq3RFqDGrvSPx5EXNoDH1fpdAAY%2BBwaIfYaD0q%2BWp2L1hcMoOdlQJoOSk42Wld0dAWfdJ7WPaAGmg5KuHTPj7oelK2NnboTJa6o4dlq5yk7YYfWztZOpK7UpB9C7YT1CMq1U0utXT1Oc3JPVZ0TBM4%2Fbsoj892EvXZ5VlUagDXa7HpSTC%2F%2B%2BTrPU0BzY5dnC%2Fd0WTTEE%2FH6KAXnqa3Lk%2FVY0qG9O2jdU%2Bs8dbu2JHig8IDeoeayJ9dy7rLaKU2LDKydcEmr73Q9Tz2onbrrDlwt%2FaTsPP20LJL7PJ69VkYWJk%2BQAZ0JrqVkJX1PIB%2FLD0t6wfPM7ep7POjFXMmp%2B735Hv5IrHYe1U55HmRQ7YQVeZjADjtp7QTtFJj0xoPQb%2FOMHVS7t%2Bfx6uH3bJawd%2Fw%2F%3C%2Fdiagram%3E%3C%2Fmxfile%3E) </p></font>

## Especialização de caso de uso 

# Casos de Uso – Sistema e-GDF

| UC01 | Realizar Login Simplificado |
| ----- | ---------- |
| Descrição | O usuário realiza login de forma simples e rápida no aplicativo |
| Ator | Cidadão |
| Pré-condições | Possuir cadastro no sistema |
| Ação | O usuário efetua login no aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta a tela de login </br> <li> O usuário insere suas credenciais </br> <li> O usuário seleciona "Entrar" </br> <li> O sistema valida as credenciais </br> <li> O sistema redireciona para a página inicial </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta a tela de login </br> <li> O usuário seleciona "Entrar com gov.br" </br> <li> O sistema redireciona para a plataforma gov.br </br> <li> O usuário realiza autenticação </br> <li> O sistema redireciona para a página inicial </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta a tela de login </br> <li> O usuário insere credenciais inválidas </br> <li> O sistema exibe mensagem de erro </br> <li> O sistema solicita que o usuário insira novamente as credenciais </br> </ul> |
| Pós-condições | Usuário autenticado no sistema |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR01, AD01](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Ana Victória](https://github.com/navicg) , 2025).</p></font>

| UC02 | Acessar Funcionalidades com Pouca Familiaridade Tecnológica |
| ----- | ---------- |
| Descrição | O usuário consegue acessar funcionalidades mesmo com pouca familiaridade com tecnologia |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário navega pelo aplicativo de forma simplificada |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta uma interface simplificada com ícones intuitivos </br> <li> O usuário seleciona a funcionalidade desejada através de ícones grandes e descritivos </br> <li> O sistema exibe instruções simples em cada etapa </br> <li> O usuário completa a ação desejada seguindo as orientações visuais </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema oferece um assistente de navegação </br> <li> O usuário seleciona a opção de ajuda </br> <li> O sistema apresenta um tutorial guiado para a funcionalidade desejada </br> <li> O usuário segue o passo a passo com dicas destacadas </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário não consegue encontrar a funcionalidade desejada </br> <li> O sistema detecta múltiplas tentativas sem sucesso </br> <li> O sistema oferece automaticamente um guia de navegação </br> <li> O usuário é direcionado para a funcionalidade através de orientação visual </br> </ul> |
| Pós-condições | Usuário utiliza as funcionalidades do aplicativo com sucesso, independente do nível de familiaridade tecnológica |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR02](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Ana Victória](https://github.com/navicg) , 2025).</p></font>

| UC03 | Receber Notificações Personalizadas por Localização |
| ----- | ---------- |
| Descrição | O usuário recebe notificações personalizadas com base em sua localização |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado e com permissão de localização ativada |
| Ação | O sistema envia notificações relevantes baseadas na localização do usuário |
| Fluxo principal | <ul><li> O usuário configura as preferências de notificação no aplicativo </br> <li> O sistema solicita permissão para acessar a localização </br> <li> O usuário autoriza o acesso à localização </br> <li> O sistema monitora a localização do usuário </br> <li> O sistema envia notificações relevantes para a região em que o usuário se encontra </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário configura manualmente suas regiões de interesse </br> <li> O sistema registra as regiões selecionadas </br> <li> O usuário seleciona categorias de notificações de interesse </br> <li> O sistema envia notificações de acordo com as regiões e categorias selecionadas </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário nega permissão de localização </br> <li> O sistema exibe mensagem informando sobre a limitação da funcionalidade </br> <li> O sistema oferece configuração manual de região de interesse </br> <li> O usuário configura manualmente a região </br> <li> O sistema envia notificações baseadas na configuração manual </br> </ul> |
| Pós-condições | Usuário recebe notificações relevantes para sua localização atual ou configurada |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR03](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Ana Victória](https://github.com/navicg) , 2025).</p></font>


**Vídeo 2** - Validação com usuário por: [Ana Victória](https://github.com/navicg).

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/MoVBjUtkhXk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/MoVBjUtkhXk" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem 
Este documento confirma que o cidadão Emanuel Maurício Costa forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1uiddHrqx33PqVEC0dZ-1_xKPa5bnoyiS/view?usp=sharing)


| Entrevistador(es) |Cidadão|Data prevista| Data Realizada  |Horário Previsto|Horário Realizado|Local|Duração|
| ---------------------------------------|------------ |------------------------ | ------ |-------|----------|-------|-------|
|[Ana Victória](https://github.com/navicg)|**Emanuel M.C** |22/06/2025| 22/06/2025| 10:25  | 10:38|   Presencial |  06:11 min |


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Ana Victória](https://github.com/navicg), 2025).</p></font>

---

| UC04 | Consultar Agendamentos e Serviços Centralizados |
| ----- | ---------- |
| Descrição | O usuário consulta agendamentos e serviços em um único local centralizado |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário acessa a área de agendamentos e serviços do aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O sistema apresenta o menu principal </br> <li> O usuário seleciona a opção "Meus Agendamentos e Serviços" </br> <li> O sistema exibe todos os agendamentos e serviços do usuário em uma interface unificada </br> <li> O usuário visualiza detalhes de cada item listado </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O sistema apresenta diretamente na tela inicial um resumo dos próximos agendamentos </br> <li> O usuário seleciona a opção "Ver todos" </br> <li> O sistema exibe a lista completa de agendamentos e serviços </br> <li> O usuário filtra por categoria ou data </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O sistema tenta carregar os agendamentos mas encontra um erro </br> <li> O sistema exibe mensagem informando sobre a falha temporária </br> <li> O sistema oferece a opção de atualizar os dados </br> <li> O usuário seleciona atualizar e os dados são carregados </br> </ul> |
| Pós-condições | Usuário visualiza todos seus agendamentos e serviços em um único local |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR04](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

| UC05 | Acessar Assistente Virtual com Acessibilidade por Voz |
| ----- | ---------- |
| Descrição | O usuário acessa um assistente virtual com acessibilidade por voz |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário interage com o assistente virtual através de comandos de voz |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona o ícone do assistente virtual </br> <li> O sistema ativa o assistente virtual </br> <li> O usuário fornece comandos por voz </br> <li> O sistema processa os comandos e executa as ações solicitadas </br> <li> O sistema fornece respostas por voz </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário ativa o assistente através de comando de voz pré-configurado </br> <li> O sistema reconhece o comando e ativa o assistente </br> <li> O usuário realiza perguntas ou solicita serviços </br> <li> O sistema executa as solicitações e fornece respostas audíveis </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário ativa o assistente virtual </br> <li> O sistema não compreende o comando de voz </br> <li> O sistema solicita que o usuário repita o comando </br> <li> O usuário fornece o comando novamente ou opta por digitar a solicitação </br> </ul> |
| Pós-condições | Usuário obtém informações ou realiza ações através do assistente virtual por voz |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR05, AD05, INT13](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

| UC06 | Acessar Tutoriais Passo a Passo |
| ----- | ---------- |
| Descrição | O usuário acessa tutoriais passo a passo sobre como usar o app |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário visualiza tutoriais detalhados sobre as funcionalidades do aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona a opção "Ajuda" ou "Tutoriais" </br> <li> O sistema apresenta uma lista de tutoriais disponíveis </br> <li> O usuário seleciona o tutorial desejado </br> <li> O sistema exibe o tutorial passo a passo com imagens e descrições </br> <li> O usuário navega pelas etapas do tutorial </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa uma funcionalidade específica </br> <li> O usuário seleciona o ícone de ajuda na funcionalidade </br> <li> O sistema exibe o tutorial específico para aquela funcionalidade </br> <li> O usuário segue as instruções apresentadas </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário busca por um tutorial que não existe </br> <li> O sistema informa que o tutorial não está disponível </br> <li> O sistema sugere tutoriais relacionados ou oferece contato com suporte </br> </ul> |
| Pós-condições | Usuário compreende como utilizar as funcionalidades do aplicativo |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR06](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

## Validação dos Casos de Uso - Artur Mendonça

Os casos de uso UC04, UC05 e UC06 elaborados por Artur Mendonça foram validados através de entrevista com usuário do sistema eGDF.

### Gravação da validação - Isaura:

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/NxpuBvQZubI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/NxpuBvQZubI" target="_blank">Clique aqui para assistir no YouTube</a></p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Artur Mendonça](https://github.com/ArtyMend07), 2025).</p></font>

| UC07 | Ajustar Tamanho de Fonte e Contraste |
| ----- | ---------- |
| Descrição | O usuário altera o tamanho da fonte e o contraste de cores do aplicativo |
| Ator | Cidadão, Usuário com Necessidades de Acessibilidade |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário personaliza configurações visuais do aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Configurações" </br> <li> O usuário seleciona "Acessibilidade" </br> <li> O usuário ajusta o tamanho da fonte usando controle deslizante </br> <li> O usuário ajusta o contraste de cores </br> <li> O sistema aplica as configurações imediatamente </br> <li> O usuário confirma as alterações </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário utiliza gestos de acessibilidade (ex: pinça para aumentar fonte) </br> <li> O sistema detecta o gesto </br> <li> O sistema ajusta o tamanho da fonte temporariamente </br> <li> O sistema oferece opção para salvar a configuração </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário seleciona "Configurações" </br> <li> O usuário faz ajustes extremos que prejudicam a visualização </br> <li> O sistema detecta configuração problemática </br> <li> O sistema oferece opção para restaurar configurações padrão </br> </ul> |
| Pós-condições | Aplicativo exibido com o tamanho de fonte e contraste personalizados |
| Data de Criação | 14/05/2025 |
| Rastreabilidade | [BR07, EN08, AD08](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

| UC08 | Ativar Modo Escuro |
| ----- | ---------- |
| Descrição | O usuário ativa o modo escuro no aplicativo |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário altera o tema visual do aplicativo para o modo escuro |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário navega até "Configurações" </br> <li> O usuário seleciona a opção "Aparência" ou "Tema" </br> <li> O sistema apresenta as opções de temas disponíveis </br> <li> O usuário seleciona "Modo Escuro" </br> <li> O sistema aplica imediatamente o tema escuro </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário aciona o botão de alternância rápida de tema na barra superior </br> <li> O sistema alterna para o modo escuro </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema está configurado para seguir o tema do sistema operacional </br> <li> O usuário tenta alterar manualmente </br> <li> O sistema informa que está configurado para seguir o tema do sistema </br> <li> O sistema oferece opção para desativar a sincronização com o sistema </br> <li> O usuário desativa e seleciona o modo escuro manualmente </br> </ul> |
| Pós-condições | Aplicativo exibido com o tema de modo escuro |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR08](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>

| UC09 | Gerar Relatórios e Comprovantes de Agendamentos |
| ----- | ---------- |
| Descrição | O usuário gera relatórios e visualiza comprovantes de agendamentos |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema e possuir agendamentos registrados |
| Ação | O usuário gera e visualiza documentos relacionados aos seus agendamentos |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário navega até "Meus Agendamentos" </br> <li> O usuário seleciona um agendamento específico </br> <li> O usuário seleciona a opção "Gerar Comprovante" </br> <li> O sistema processa e exibe o comprovante </br> <li> O usuário visualiza e tem opções para salvar ou compartilhar </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário navega até "Relatórios" </br> <li> O usuário seleciona o tipo de relatório desejado </br> <li> O usuário configura os filtros (período, tipo de serviço) </br> <li> O sistema gera o relatório conforme os parâmetros </br> <li> O usuário visualiza o relatório com opções para exportar </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta gerar um relatório </br> <li> O sistema identifica que não há dados para o período selecionado </br> <li> O sistema exibe mensagem informando a ausência de dados </br> <li> O sistema sugere outros filtros com dados disponíveis </br> </ul> |
| Pós-condições | Usuário obtém o documento (comprovante ou relatório) desejado |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR11](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab), 2025).</p></font>>

| UC10 | Alterar Idioma do Aplicativo |
| ----- | ---------- |
| Descrição | O usuário altera o idioma do aplicativo |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário modifica o idioma da interface do aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário navega até "Configurações" </br> <li> O usuário seleciona a opção "Idioma" </br> <li> O sistema apresenta os idiomas disponíveis </br> <li> O usuário seleciona o idioma desejado </br> <li> O sistema aplica o novo idioma imediatamente </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário inicia o aplicativo pela primeira vez </br> <li> O sistema detecta o idioma do dispositivo </br> <li> O sistema pergunta se deve usar o idioma do dispositivo </br> <li> O usuário pode confirmar ou selecionar outro idioma </br> <li> O sistema aplica o idioma selecionado </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário seleciona um idioma </br> <li> O sistema encontra um erro ao carregar o pacote de idiomas </br> <li> O sistema mantém o idioma atual </br> <li> O sistema notifica o erro e sugere tentar novamente </br> </ul> |
| Pós-condições | Aplicativo exibido no idioma selecionado pelo usuário |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR13](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo autor ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025).</p></font>

| UC11 | Personalizar Preferências e Perfil para Recomendações |
| ----- | ---------- |
| Descrição | O usuário personaliza suas preferências e perfil para receber recomendações de serviços |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário configura suas preferências para receber recomendações personalizadas |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário navega até "Meu Perfil" ou "Preferências" </br> <li> O usuário seleciona categorias de interesse (saúde, educação, etc.) </br> <li> O usuário configura dados demográficos relevantes </br> <li> O usuário define regiões de interesse </br> <li> O sistema salva as preferências </br> <li> O sistema passa a exibir recomendações personalizadas </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo pela primeira vez após login </br> <li> O sistema sugere configuração de preferências </br> <li> O usuário responde a um breve questionário </br> <li> O sistema cria um perfil inicial baseado nas respostas </br> <li> O sistema exibe recomendações baseadas no perfil inicial </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta salvar preferências incompletas </br> <li> O sistema identifica dados essenciais faltantes </br> <li> O sistema destaca campos obrigatórios não preenchidos </br> <li> O usuário completa as informações necessárias </br> <li> O sistema salva as preferências </br> </ul> |
| Pós-condições | Perfil do usuário configurado para receber recomendações personalizadas |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR14](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo autor ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025).</p></font>

| UC12 | Receber Mensagens Curtas sobre Vencimentos e Lembretes |
| ----- | ---------- |
| Descrição | O usuário recebe mensagens curtas sobre vencimentos e lembretes importantes |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema e ter notificações ativadas |
| Ação | O sistema envia mensagens curtas sobre prazos e vencimentos relevantes |
| Fluxo principal | <ul><li> O usuário configura notificações no aplicativo </br> <li> O sistema monitora prazos e vencimentos associados ao usuário </br> <li> O sistema identifica um prazo se aproximando </br> <li> O sistema envia notificação com informação concisa </br> <li> O usuário recebe e visualiza a mensagem </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário navega até "Central de Mensagens" </br> <li> O sistema exibe todas as mensagens e lembretes enviados </br> <li> O usuário seleciona uma mensagem para ver detalhes </br> <li> O usuário configura a frequência de lembretes </br> </ul> |
| Fluxo de exceção | <ul><li> O sistema tenta enviar uma notificação </br> <li> O sistema detecta que o usuário desativou as notificações </br> <li> O sistema armazena a mensagem na Central de Mensagens </br> <li> O sistema exibe um contador de mensagens não lidas na próxima vez que o usuário acessar o aplicativo </br> </ul> |
| Pós-condições | Usuário informado sobre prazos e vencimentos importantes |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR15](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo autor ([João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS), 2025).</p></font>

---

**Vídeo 4** - Validação dos Casos de Uso 10, 11 e 12 com usuário por [João Marcos Moraes](https://github.com/JJOAOMARCOSS)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/1e08GOCXsCU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/1e08GOCXsCU" target="_blank">Clique aqui para assistir no YouTube</a></p>

| Participante   | Entrevistador                                                                                              | Data       | Horário       | Local       |
| -------------- | ---------------------------------------------------------------------------------------------------------- | ---------- | ------------- | ----------- |
| Thalison Felipe | [João Marcos Moraes](https://github.com/JJOAOMARCOSS) | 21/06/2025 | 15:10 - 15:25 | Presencial |


## Termo de consentimento de imagem 
Este documento confirma que a cidadão Thalison Felipe forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://github.com/Requisitos-de-Software/2025.1-e-GDF/blob/docs/corre%C3%A7%C3%A3o-de-erros/docs/assets/termo-img/Assinatura%20com%20todos%20os%20participantes%20.pdf)

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelos autores ([João Marcos](https://github.com/JJOAOMARCOSS), 2025)</p></font>

---

| UC13 | Implementar Funcionalidades Educacionais Adicionais |
| ----- | ---------- |
| Descrição | O aplicativo implementa funcionalidades adicionais na área educacional, como acompanhamento de pendências para professores e alunos |
| Ator | Cidadão (Professor/Aluno) |
| Pré-condições | Estar autenticado no sistema com perfil vinculado à rede educacional |
| Ação | O usuário acessa funcionalidades específicas da área educacional |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O sistema identifica o perfil educacional (professor/aluno) </br> <li> O sistema exibe o módulo educacional personalizado </br> <li> O usuário seleciona "Acompanhamento de Pendências" </br> <li> O sistema exibe lista de pendências organizadas por categoria e prazo </br> <li> O usuário visualiza detalhes de cada pendência </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O sistema exibe o módulo educacional </br> <li> O usuário seleciona "Calendário Acadêmico" </br> <li> O sistema exibe o calendário com eventos, prazos e compromissos </br> <li> O usuário pode filtrar por tipo de evento </br> <li> O usuário adiciona eventos ao calendário pessoal </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta acessar o módulo educacional </br> <li> O sistema não encontra vínculo educacional ativo </br> <li> O sistema exibe mensagem informando sobre a necessidade de vínculo ativo </br> <li> O sistema oferece informações sobre como regularizar o vínculo </br> </ul> |
| Pós-condições | Usuário acessa e gerencia informações específicas da área educacional |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [EN06](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>

| UC14 | Receber Notificações por Categorias |
| ----- | ---------- |
| Descrição | O usuário recebe notificações por categorias como saúde, educação, transporte |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema e ter notificações ativadas |
| Ação | O usuário configura e recebe notificações segmentadas por categorias |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário navega até "Configurações de Notificações" </br> <li> O sistema exibe as categorias disponíveis </br> <li> O usuário seleciona as categorias de interesse </br> <li> O sistema salva as preferências </br> <li> O sistema envia apenas notificações das categorias selecionadas </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário recebe uma notificação </br> <li> O usuário acessa a Central de Notificações </br> <li> O sistema exibe notificações organizadas por categorias </br> <li> O usuário filtra para visualizar apenas uma categoria específica </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário desativa todas as categorias de notificação </br> <li> O sistema detecta que nenhuma categoria está ativa </br> <li> O sistema exibe alerta sobre a possível perda de informações importantes </br> <li> O sistema sugere manter pelo menos uma categoria ativa </br> <li> O usuário decide manter ou não categorias ativas </br> </ul> |
| Pós-condições | Usuário recebe apenas notificações das categorias de seu interesse |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR19](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>

## Validação dos Casos de Uso - Lucas Mendonça

Os casos de uso UC13 UC14 elaborados por Lucas Mendonça foram validados através de entrevista com usuário do sistema eGDF.

### Gravação da validação - Tiago M:

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/pt2Nl6jnv6I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/pt2Nl6jnv6I" target="_blank">Clique aqui para assistir no YouTube</a></p>

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Lucas Mendonça](https://github.com/lucasarruda9), 2025).</p></font>

---

| UC15 | Acessar Informações de Agendamento Centralizadas |
| ----- | ---------- |
| Descrição | O usuário acessa informações de agendamento e reagendamento de forma centralizada |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário visualiza e gerencia todos seus agendamentos em um único local |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário seleciona a opção "Meus Agendamentos" </br> <li> O sistema exibe todos os agendamentos ativos em ordem cronológica </br> <li> O usuário seleciona um agendamento específico </br> <li> O sistema exibe detalhes completos do agendamento </br> <li> O usuário visualiza opções para gerenciar o agendamento </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário seleciona a opção "Reagendar" em um agendamento </br> <li> O sistema exibe horários disponíveis </br> <li> O usuário seleciona novo horário </br> <li> O sistema confirma a alteração </br> <li> O sistema atualiza o agendamento com as novas informações </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta reagendar um agendamento </br> <li> O sistema verifica que o prazo para reagendamento expirou </br> <li> O sistema exibe mensagem informando sobre a impossibilidade </br> <li> O sistema oferece opções para novo agendamento </br> </ul> |
| Pós-condições | Usuário visualiza ou gerencia seus agendamentos de forma centralizada |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR17](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Karoline Luz](https://github.com/KarolineLuz), 2025).</p></font>


| UC16 | Reportar Problemas da Cidade via Mapa Interativo |
| ----- | ---------- |
| Descrição | O aplicativo permite que usuários reportem problemas da cidade através de um mapa interativo |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema |
| Ação | O usuário reporta problemas urbanos usando um mapa interativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário seleciona "Reportar Problema" </br> <li> O sistema exibe um mapa interativo da cidade </br> <li> O usuário navega pelo mapa até localizar o ponto do problema </br> <li> O usuário marca o local exato no mapa </br> <li> O usuário seleciona a categoria do problema </br> <li> O usuário adiciona descrição e fotos </br> <li> O usuário confirma o envio </br> <li> O sistema registra a ocorrência </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário permite que o aplicativo use sua localização atual </br> <li> O sistema exibe o mapa centralizado na localização do usuário </br> <li> O usuário ajusta a marcação, se necessário </br> <li> O usuário preenche os detalhes do problema </br> <li> O sistema registra a ocorrência com a localização GPS </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta reportar um problema </br> <li> O usuário não consegue marcar a localização precisa </br> <li> O sistema oferece a opção de buscar por endereço </br> <li> O usuário digita o endereço da ocorrência </br> <li> O sistema localiza e marca o endereço no mapa </br> <li> O usuário completa o registro da ocorrência </br> </ul> |
| Pós-condições | Problema urbano registrado no sistema com localização precisa |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [EN09](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Karoline Luz](https://github.com/KarolineLuz), 2025).</p></font>

---

**Vídeo 5** - Validação dos Casos de Uso 15 e 16 com usuário por [Karoline Luz da Conceição](https://github.com/KarolineLuz)

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/5zFdG7kKD6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/5zFdG7kKD6s" target="_blank">Clique aqui para assistir no YouTube</a></p>

## Termo de consentimento de imagem 
Este documento confirma que a cidadã Júnia Luz de Sousa forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1tAtNRMAKPoStT9ZyOU-DdT1I9mJgC5qK/view?usp=sharing)


| Participante    | Entrevistador                                         | Data       | Horário       | Local      |
| --------------- | ----------------------------------------------------- | ---------- | ------------- | ---------- |
| **Júnia L.S** | [Karoline Luz](https://github.com/KarolineLuz) | 19/06/2025 | 16:50 - 16:55 | Presencial |


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Karoline Luz](https://github.com/KarolineLuz), 2025).</p></font>

---

| UC17 | Autenticação Segura via Plataforma gov.br |
| ----- | ---------- |
| Descrição | O aplicativo permite autenticação segura através da plataforma gov.br, com opções como reconhecimento facial |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado e conta na plataforma gov.br |
| Ação | O usuário realiza login através da integração com a plataforma gov.br |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta a tela de login </br> <li> O usuário seleciona "Entrar com gov.br" </br> <li> O sistema redireciona para a autenticação da plataforma gov.br </br> <li> O usuário insere suas credenciais gov.br </br> <li> O usuário seleciona reconhecimento facial como segundo fator </br> <li> O sistema solicita o reconhecimento facial </br> <li> O usuário realiza o reconhecimento </br> <li> O sistema valida a autenticação e retorna ao aplicativo </br> <li> O usuário é autenticado no aplicativo </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo </br> <li> O sistema apresenta a tela de login </br> <li> O usuário seleciona "Entrar com gov.br" </br> <li> O sistema redireciona para a autenticação da plataforma gov.br </br> <li> O usuário insere suas credenciais gov.br </br> <li> O usuário seleciona outro método de segundo fator (código via SMS, token) </br> <li> O sistema processa a verificação do segundo fator </br> <li> O usuário completa a verificação </br> <li> O sistema valida a autenticação e retorna ao aplicativo </br> <li> O usuário é autenticado no aplicativo </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta realizar login com gov.br </br> <li> O sistema redireciona para a autenticação </br> <li> O usuário insere credenciais incorretas </br> <li> O sistema gov.br exibe mensagem de erro </br> <li> O usuário tem opção de recuperar acesso ou tentar novamente </br> </ul> |
| Pós-condições | Usuário autenticado no aplicativo com credenciais seguras da plataforma gov.br |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [EN04](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ( [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC18 | Compartilhar ou Salvar Informações Importantes |
| ----- | ---------- |
| Descrição | O usuário compartilha ou salva informações importantes como protocolos ou comprovantes |
| Ator | Cidadão |
| Pré-condições | Estar autenticado no sistema e ter informações para compartilhar/salvar |
| Ação | O usuário exporta ou compartilha informações do aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário navega até o documento/informação desejado </br> <li> O usuário seleciona a opção "Compartilhar" </br> <li> O sistema exibe as opções de compartilhamento </br> <li> O usuário seleciona o método de compartilhamento </br> <li> O sistema exporta a informação no formato adequado </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário acessa o aplicativo e faz login </br> <li> O usuário navega até o documento/informação desejado </br> <li> O usuário seleciona a opção "Salvar" ou "Download" </br> <li> O sistema salva o documento no dispositivo </br> <li> O sistema confirma o salvamento bem-sucedido </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário tenta salvar um documento </br> <li> O sistema identifica falta de permissão de armazenamento </br> <li> O sistema solicita permissão para acesso ao armazenamento </br> <li> O usuário concede a permissão </br> <li> O sistema conclui o salvamento </br> </ul> |
| Pós-condições | Informação compartilhada ou salva conforme solicitado pelo usuário |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [BR20](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ( [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>

| UC19 | Acessar Seção de Suporte ao Usuário |
| ----- | ---------- |
| Descrição | O aplicativo oferece uma seção de suporte ao usuário com instruções de uso |
| Ator | Cidadão |
| Pré-condições | Ter o aplicativo instalado |
| Ação | O usuário acessa informações de suporte e instruções de uso |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <li> O usuário navega até "Suporte" ou "Ajuda" </br> <li> O sistema exibe categorias de suporte disponíveis </br> <li> O usuário seleciona a categoria desejada </br> <li> O sistema apresenta instruções detalhadas ou FAQs </br> <li> O usuário lê as informações de suporte </br> </ul> |
| Fluxo alternativo | <ul><li> O usuário está em uma funcionalidade específica </br> <li> O usuário seleciona o ícone de ajuda contextual </br> <li> O sistema exibe instruções específicas para aquela funcionalidade </br> <li> O usuário visualiza as instruções sem sair da tela atual </br> </ul> |
| Fluxo de exceção | <ul><li> O usuário busca por um tópico de suporte específico </br> <li> O sistema não encontra informações sobre o tópico </br> <li> O sistema exibe opções de contato direto com suporte </br> <li> O usuário seleciona o canal de suporte preferido </br> <li> O sistema conecta o usuário ao suporte escolhido </br> </ul> |
| Pós-condições | Usuário obtém as informações de suporte necessárias |
| Data de Criação | 18/05/2025 |
| Rastreabilidade | [EN09](https://requisitos-de-software.github.io/2025.1-e-GDF/elicitacao/req_elicitados/) |

**Vídeo X** - Validação dos casos de usos 17, 18 e 19.

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/2RsMT-1wq4M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://youtu.be/2RsMT-1wq4M" target="_blank">Clique aqui para assistir no YouTube</a></p>

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo autor([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

## Termo de consentimento de imagem 
Este documento confirma que o cidadão Gabriel Souza forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/1Vx3nkS_CSteiuCCOe2M4GVtsV7QjfV8V/view?usp=share_link)

| Entrevistador(es) |Cidadão|Data prevista| Data Realizada  |Horário Previsto|Horário Realizado|Local|Duração|
| ---------------------------------------|------------ |------------------------ | ------ |-------|----------|-------|-------|
| [Luiza da Silva Pugas](https://github.com/Luizaxx) | **Gabriel Souza** |19/06/2025| 21/06/2025| 15:30  | 15:50| Presencial |  1:18 min |

<font size="3"><p style="text-align: center"> Fonte: Elaborado pelo autor([Luiza da Silva Pugas](https://github.com/Luizaxx), 2025)</p></font>

---

## Referências Bibliograficas

[1] DevMedia. *O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML*. 2012.  
Disponível em: [https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408](https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408).  
Acessado em: 13 de Maio. de 2025.

[2] SERRANO M., SERRANO M. *Requisitos - Aula 13*.  
Disponível na plataforma Aprender3: [https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/3096118/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf).  
Acessado em: 13 de Maio. de 2025.


## Histórico de Versões

| Versão | Descrição                                           | Autor(es)                                                                 | Data       | Revisor(es)                                         | Data de revisão |
|--------|----------------------------------------------------|---------------------------------------------------------------------------|------------|----------------------------------------------------|-----------------|
| 1.0    | Documentação do Diagrama de Casos de Uso          |  [Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx) | 16/05/2025 | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)       | 17/05/2025      |
| 1.1    |  Adicionando tabelas de casos de uso e Bibliografia | [Ana Victória](https://github.com/navicg) e [João Marcos Moraes](https://github.com/JJOAOMARCOSS)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 15/05/2025 |
| 1.2    |  Edição de imagem do diagrama e correção de liks| [Ana Victória](https://github.com/navicg)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.3    | Adição de casos de usos não implementados no documento | [Artur Mendonça Arruda](https://github.com/ArtyMend07) |16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.4    | Elaboração e adição de casos de usos não implementados | [Gabriel Lopes](https://github.com/BrzGab)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.5    | Criação e adição de tabela dos casos de uso 10, 11 e 12 no artefato. | [João Marcos Moraes de Andrade](https://github.com/JJOAOMARCOSS)|16/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.6    | Adição do casos de uso 13, 14 no artefato. | [Lucas Mendonça](https://github.com/lucasarruda9)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.7    | Adição do casos de uso 15(solicitação de serviço público) no documento. | [Lucas Mendonça](https://github.com/lucasarruda9)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.8    | Implementando os casos de uso 16, 17 e 18 no artefato. | [Karoline Luz da Conceição](https://github.com/KarolineLuz)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 1.9    | Adicionando os casos de uso 19.| [Luiza da Silva Pugas](https://github.com/Luizaxx)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 17/05/2025 |
| 2.0    | Ajustes nos casos de uso | [Gabriel Lopes](https://github.com/BrzGab)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 1.10    | Ajustes nos casos de uso | [Gabriel Lopes](https://github.com/BrzGab)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) e [Artur Mendonça Arruda](https://github.com/ArtyMend07) | 18/05/2025 |
| 2.0    |Adicionando Entrevista presencial | [Karoline Luz](https://github.com/KarolineLuz)|20/06/2025|[Ana Victória](https://github.com/navicg)| 22/06/2025 |
| 2.1    |Adicionando Entrevista presencial | [Luiza da Silva Pugas](https://github.com/Luizaxx)|21/06/2025|[Ana Victória](https://github.com/navicg)| 22/06/2025 |
| 2.2   | Adidionando validação dos Casos de Uso 01, 02 e 03 |[Ana Victória](https://github.com/navicg)                                            | 22/06/2025 | [Karoline Luz](https://github.com/KarolineLuz)                                                | 22/06/2025      |
| 2.3    | Adição da seção de validação dos casos de uso do Artur Mendonça | [Artur Mendonça](https://github.com/ArtyMend07)|22/06/2025| [Lucas Mendonça](https://github.com/lucasarruda9) | 22/06/2025 |
| 2.4    | Adição da validação dos casos de uso 13 e 14 | [Lucas Mendonça](https://github.com/lucasarruda9) |22/06/2025| [Artur Mendonça](https://github.com/ArtyMend07) | 22/06/2025 |

