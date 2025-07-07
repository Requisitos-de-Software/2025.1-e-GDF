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

<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/gb_imagenss/docs/assets/modelagem/casos_de_uso/Diagrama%20de%20Casos%20de%20Uso.drawio%5BATUALIZADO%5D.png"><img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-e-GDF/refs/heads/gb_imagenss/docs/assets/modelagem/casos_de_uso/Diagrama%20de%20Casos%20de%20Uso.drawio%5BATUALIZADO%5D.png" alt="diagrama-casos-de-uso-2" border="0"></a>


<font size="3"><p style="text-align: center">Fonte: Elaborado pelo autor ([Gabriel Lopes](https://github.com/BrzGab) e [Luiza da Silva Pugas](https://github.com/Luizaxx), 2025).</p></font>


<font size="3"><p style="text-align: center"> Disponível de forma online em PDF:  [Clique aqui](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Diagrama%20de%20Casos%20de%20Uso.drawio&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22P%C3%A1gina-1%22%20id%3D%2234NzMq-ass0gtIXJ2DlH%22%3E7V1Zd5tIFv41PmfmQTpUsT8qsrNMlnbidJZ%2BmYMlbJGRQAHkOPn1U8UmuJQkhKhSYdMPaQnJuMzdv7tdqNPV46vQWS%2FeB3N3eYGV%2BeOFenmBsWbbJvkfvfI7vaIaipFeuQ%2B9eXoNbS%2FceH%2Fc7KKSXd14czeqfDEOgmXsrasXZ4Hvu7O4cs0Jw%2BBX9Wt3wbL6W9fOvVu7cDNzlvWrX715vEivWtjcXn%2FteveL%2FDcjw04%2FWTn5l7O%2FJFo48%2BBX6ZJ6daFOwyCI01erx6m7pE8vfy7pz73c8WlxsND14yY%2FcI3ieBp%2Bu1x%2F%2Frl58%2Fq18fgYvRvh9C4PznKT%2FcEX2FiS%2B72Yew%2Fk5T19mV%2B6C8hvIn9ITiTj54Ye%2FoW6fQl%2F5DaEV8gB0%2FvULjN%2B43CI4RDDIYZDDIfo%2ByGYd%2BzR%2BYdDDIcYDjEcYjjEcIjhEMMhhkMMhxgOMRxiOMRwiGd5iMMBfQJ6x79zJD0MNv7cpWC0Qj7%2BtfBi92btzOinv0JnTa4t4tWSvEPFT5fB7QzvfnDD2H0sXcrA7ldusHLj8Df5SvbpCCsZ8p7lHkaqlV34tUXy7TzRsCih%2BJqdf9PJ0gf3xe23CDt5kYHsRwDu5k7APadq8cRyWtIPRimxJ%2BQLyFo%2Fpk8d0Hoyc6PIIWRR3vixG97RZ4uVG2%2B1Xnp33syZOztpD0hF%2Fg5vHbliyIQ0SKY6lQpSlqnEjUY5S%2FAg0jTwo80yTsg0JU8tdJKEGaXU5N71586KXAwi8jYhnhs%2BeBdT9WJi0mtSUk%2BvUE9jyBhWRVJPRRyp582deUIPNWhKjmjhrOnLzWo5mcVBSL5Dny8RyOU759ZdXgeRF3uBT75yG8RxsCp9YbL07ukHcQBIF2zipee70yLrqXRET1OtSiOy9TpBEUsckc2NoruzlLf5Y7%2FxothdOVRuRq8uX5aIc7uTMuSZxNXH6mTPe%2BZSDcogxMqbz5e7RKtq4ShTZPlsrHVDnbqqNBtKm8GNNjo%2FaftCyDFPNWXozl1%2F5jmelFpQ0wFdiuddposmVAsa%2FOhC%2Fu%2Bs6FNc1t95%2Fmy58cLiYvUH9nuggIIlGkExLBTlkmrQF87sf%2FeJ8E2DJVWwl37gU8oTezqhNSDkSrB2%2FfTKS48%2ByURE5060SOQV1aR3J1dEwSacZSe8%2Bsf%2F%2FTP49p%2FNzY%2FFS%2B3rj9XfwcuRmn6PmPh7N24gOe68UoGyk8mUMUKqDfisrppzzgvdpRN7D9UyFhabZb%2FwOvAStsgZHldZWjMBp6bPIfupctkJuJGOqjdSdXCj9EHVbkQI5%2FwufW1NvxCxf1X%2BneDuLnIrd0lkp3iW7cVJV%2FmJ09Z0vQoexklc9fQcC8tuYLpsllsBGa8zFalrImiauPYfgjgJwVJXnv77Qncbm7JeExqzgm4Wnbm5KDpHFwXQmTyOZUCeuvenROqnGitYVpXSNhpjvU5rnUFraAO6ozVXt0cB5P7kzsi5SdD%2BDIiNrHE10kc2A6gRHBnqHOG0mmiHkMzpB5fBbJODNk%2BR8BiQXTs%2FIJCbigrZYfy39f2zaKD0sKq%2Bvvvoxd%2ByT%2Bjr7%2FT6WAX%2FZR9ePpZ%2B6vJ36c21G3rk76O4QXrNJ3%2Frt%2FKb9MZ6%2FnZ7q%2BTd70NEK4cee6GvcuwRv39z9VPbzL9%2FXc8W3o%2BP%2F7y21FH2vYOhR4nEOoPCejexxkgFuAaxDy2jjRFSYSiOmsUbXUUKBgt%2B7Jo39f3MuIPxWBy9hw%2BTd5CpT2BOvc6ce2MtSbgTujmG1pI3bcCaOtSPvDmTFe8MWpOpNdnIjikVY25RxjzUwlhtqTYtYOQLEFkUb7JitIE3m1t0Qy7WREBpIltvy5rQoiPRrMkKKU9gzZY8xImlu2XNvel0WXizQB4LbxNyVGPerLEmBCt586Y98OZJJh3bcvEmBmkXZKpdmXQE%2FVbOvJmLwsCbLXlTw3LxJszkIWyolQept%2BVUqEWxYE7tOGR%2FdpxqNE1li7LwCtSiSmvvUwFq1BStRlmZ54E5mcz5YF5foo%2FX7sfpWyV8q5t%2FLVYT2bBOGLQjE2q75rxZg00Fh0Zmx4jSU%2BZNpuI0ZUOUYGhkwUxta8WJRQPx5hC3n5gkkixur8GdygmaEzCnJtqqWwNznqQ5Lck1Zz37fYTmBLfSYGkUb%2BYcUKXTmNOWLHKvMafWPr8OzbohOFjPwYKBOdv6nJKZdRis15si2gfrtmA83uKFJI0VRasyqGqi87Bo12UhjZWqZBa%2Fxrdqa4tv22N7%2B5%2BR9%2B5sK6gFczEeVOxJrIoUuUqYRliFDkDr0OkAr9qwBIU3rw7w6Km8asnFqyqG%2FsAJkZS2j1nVGoDQHbPG3z99v1Ov3iydHwtrvvmy%2Bv1hOsp5c2DWlqUkkrkAMCNqW50kRBFooTL52X82mw469cTMvWQqtVZVYuhWW5WKMOwD0vlhp0z2zMlQ5kbyoG%2Byt0EYL4L7wHeWV9urgCW333kX0EaahMd%2BuHH8O5vY4GzioMrTOTdui%2B%2B%2Flz5hs99OVjvIGCdSXAfFP9hsW%2BJ2%2BE7dUZvtnzB0EZ8Or8kmJnSqdOk%2B2W4%2B2I1ddGSWNJLFq3OTXYnHj8775lVcERYgiiHs%2FcCKwsoWsNBxVjZ%2FXfqp4%2FVam%2BEYJzWoZfwsdjaGCTuC2ipXYJYb96qdbTbGPprykNxP7myzdsNkBtCN6y%2BknGCHTBO4RCPMUKdIZ%2BjTLub%2FsF1QBlFOcOGfdBfiPr9DEhceqhwzLw4%2BVuVYOYye34hfVQ47b38eM%2F9UxlJ1KYj8utbMhjLWtPniLFa%2BcHVzK9%2B27xerOrgROEsvrDyrJqSrwbXr0I0IkyVm%2FpIIVJSHZB%2BcB%2Fe%2BXTwm0gPQUc0DYM1GYdkHbg4AzyG2O2YcKZ4%2F96I1iXHplcsHugtSRmLB1lQGqQyhpOKIcXwhnhOdPEZFi3hRKy%2BKtuPHUiF7d8rEqnNSjjFBTjDhBtCiG3fmGPChVBRj24UPk%2F6kgUxu4cReLdtZf%2F5ZXB3VrFqvWo9TU1eHRMIGVjSsaxa2TNtGVU2rWWNN1XWEFcUwdMsCSYhe%2BEGII9zxLCKYU7OBY6Ua%2FGi6vV9ftM0B7pPjw%2FCB1AgmgP9rIzWayruqA8Vh9TG0QSKGz0gOlu1l4sMju%2BRqADZgj6XSlsFtA04%2FVJoZrc54kzXhcuBNtufVB940YW96LenTuExIgeXuekOPqivmxBwxhiw5T6NUus7oPnTmyVqcf90kgeqLCY1dybGVq%2FmmlrKn1z%2BHjh%2BtAxJc%2FvtJ5vBtwEjFzMxyCp%2FBx50M2mazA8dwmDiXcZoHBGuSCIXJv1OHsEgQelImCHVIKRY4aIoELpgVfp0Jrj8LA9%2F7k8K5mdjOe7HOSgOOcdEWXKYUa3o9P0qxErkDxCRikUuuzrobcHeWWE%2BzqlXvVtvWD7hP0VK1Rt6GXMEeZgV7A34jDL9RxjSmKkcfxoHwo9MablbYsNdEyinUCES4dts5LRqYhIGUXtag4Y6HvTyZMJllxPbGcpKEyZDBtbZN4TBMQqYmOEgeEJz9GrZvrGnAIVmtK4OQqlar8bANx73yZk6OZT0Utgmde%2BrzKDPilJDQPYooqkOukzdfvDDeJNuP0xD%2BS%2FBHxpBwhBAo32Ls9kQsoIVbTJjDB1yi92Dpzbw4q7iuhOs51BKsHH9erD%2BSlGwa6FsyWJiL0Eie517q6zAolr%2F3hT6wj7CYg3k%2BCmF%2BFHoWWEtPepAah4By1yfDJL5itRxyXMuWNpyaJFcIqA6FOectzBEivLlMHl7WJHUBTm2pjdI2viWeTfVOqJdldTmWLKDPm25t9RfuzEtyiC38pF6niU1GayK3vdtsUg%2FlVic6JrmwSAKIWFCZ2bDEoDEgQqKAyq0Iu4oFRNQBSN5vT%2FvGnEaNOdumSraVWudC61SO664nBYDweRPTShovL70K6eOXs15jhMAIBevszVwqxw7nCji3SWrbyKvJnFyks4xkpFAd57FYSBxr1gw%2FEonqZb12oog6mM72tXwUgtVpNqvmSWh1Wn6AAYcTjMOd4B1YTb2DpiMczxOWH9yD3HjOBqzyNsAwyF5E5RrHnMWAqcmCqalN53WoUgPitTWSbWW3pgVUu5fCi%2FkJ7zTw77z7TVaRT0MH79ZbenMnxdK8aCOnO1rfJq6wpggITedrPKFPZ%2FmQZYUzgm07ZcozICAJ5aMcdFORcn4%2FlWMp8WS9zKZ27KacS2tqPrurNY0xPrlySpxmA2WKzk83FsY3xBcyxxe5juxuafaZcvbQs4BZlsZzmaGzA5ck9MNF4QhoDvGFLPFFLpOHhbdpq%2FZZhPegyDXf7wD7tuGmiH4IL0eke0LolHg%2F74OklPEqmm1CKeHTekRROC5niyh0jhHFdRjch84qDfwoleAQwMmGKj36FiXD9CWkma7Ulljgs3ulupBo4nNaCCOvPNXiPPX8lBniha7clLFt2lVXRVOtQ85Kt4UMeuNQoukWn7N4IxhpVTkxYDt22%2FJfvZehhD6EEucNJcYKGMynG9begKJ1Y%2FdeaT0o1o3nQUmRxKjtfmudxLAarumSTKw51mpMgxXhtNhbLvLGqXUYPDhJe6J8jpFm15xW5ngaoa5RzvVcRj4F4crJhsIHs01erU0eIvVg36xopU0k8bjqGvJ9%2FrlPxpny%2BU%2FSk7WBJ6sKnj2dq8ayxXswry%2FRx2v34%2FStEr7Vzb8Wq4ncy7SwgYEfm2%2BoOXqUCfRjG24qlMvg5Y9j8GOfCCS%2BTyQPOqu5kMkpu6o11vXSgm04S0hXW66ZxWb1b0CW2UeE3GC1pEKP5Dk2k7BMF3t4r1wbv2EzCVZbh2eqVbV7WMNim0kMVpJgYM6tzu0bc5omZM7Wk6WxDuYSWYZg5uSYDKnULr6Ze8FKyiRVPbHInJAiNn7kmAm5JMI7iytESXOJDvUgV660sIx8VOLZJrjNJIbOfCP%2FzjCYTmS2nwldzWucaQfq0wNhBIwZ6jZJYTRdH2RInaTARnWkNLLNlrlHBEGb2uiAfgR6HLMUA2jTQKLHNglnKlJtC5XrplvFDbnbH2F4q7SeFa9XNQQJKXAP5Tp327gU0rlhRLv2s0UZ5O2dRw9E23GuQ%2FeOsCV1qyb%2BzHMkHb6gwbXHyD6782tyTHF9cufunecnE217QSLNtsZmExIZRW5ZDJEwPyJN6FThTKgYk79WdHuQ9GFLPdlPdLFep5vQ%2BajmmSYsDoHL2QMXs2nCKtf1cjo4MHCh3YjtHBwLSmcviybzsG2IW55IsnmvTB4WXiyz8Oa7hbci1za7DIOTogalX8I7zNFsbqzYCTyjIb8LSuCBYXbb3MLxCTwFLhYRPEfTHOZo7texfWPOWulDrbyuMXNCmElVFMHMyTFBRmJM95bGKso7d3UbEp6JMlBnsiT%2BiZw4wQipwJ9FCiPaFAvkcEyTVUoAXobuz80WyMnBghL55COYjiD0hplzVTShqA7HLMgXooDvsszzdej8SRYSXVNYwO8PiTAz9yxSqCyOgPbzgHCErqoxmza1mVLnlWBXG1bb5pXgvGes9rKrzeKYpBhwl0b5Yg1XJNjQtb0y3DGc2nTiZm5S5ZRrpMOAtW05tFoLfaEJ7Idcc8yQlIe%2Ff3Kde5rHynoi5XN%2BGPkrjTUWR%2Bhofosj2n1DVGsY%2BFne8dKZB9vZmpKTqlY2zlhwihWhhOJY%2FT14qQfhsrFtF4Y0%2B0nTOGRZu0XJckVaNpDx%2BzdXP7XN%2FPvX9Wzh%2Ffj4z2tLHeUtDnIaSGyAnIUG%2BygaG0h1rFimiUhYaZCbIADvaioam7ZFPtNNBRngoP2wnWeasjT4xIVPbOUaIm9o5%2BQT75Xkgz5xbsYlFXlacWWammHoiDjIWn7aQlJ1bWyoJjYNcipL0UBfa2N9ADWAgfq49tHiiMRXQN4PQZzgh7Uh2tlScyd27%2BnWKxk9tBo6rzJ2OIoF5y2eW668pUuBeECXdNI5oaYnbzNYDehirSMTuuvK4rnrqlRpySiHTaOfuuBJWnKJTRiyqoyIVWwgZA9w%2FRkDIWHT7a2mML8lNcyvIgD5GG030sO2sG31Qa%2B8G3uA%2BTsKacaKAaTRsA8W7mwDGxOA%2FdbxtdNdAxxNMwCW3BkAiNubbTN7qmJV72TpfUQxbMxP5MG8SupdFfudigmJUtZCjBAYDYWZUxKEDsm3eeZqcrIkK5o%2BbB7o%2F%2BUji2YaYwxtNqtGRWiaxuaYptk%2FU7QkYPKmazRUo5mtMAIVbApt6bOHnM1zCFVsRmJmryGU029RFQjUtJ6VBcbnY6uXEyzsIfvyDDrBcqE8LL1S51hq8IDdthcB9nGSKKSX0stz4teGGNg4K71%2BSJD4V8HD%2BDaU0TsaQXWsIsZ%2BX8EgLs89aWXipKksOuTAX7gzL3duXzozOfNamlabTqEiRlyIsUhyIYUj6P7FoRuWKZmmoTtP0lxeJLVEaQagEGYJFBJLoWGNwbOINZqmRWyp0yIwKawqMEJovtMH3qmX3gpS8Hnkdwg2ioyIblVE3xQ5TMZumvsoTLGcgl33NVuPy6vdyW7WES2bYHPE1Cczis76i2xanj%2BvFptczTcz4ugGfuJQyedHkcikVsRlnt2R4gi1D46UNI5U0czfQOOqMmtcVYfBiN7WlQJj21UMW9d6onE5pl22oyx2Vs%2FO02mlaT%2B%2BfEoX9japGiN4FTtEESkckfZqFxoxmBflGZhX0SxYOnKiDBAHMlglzpbYlCZShp3CksUpBhYZqBTWsIHdbDqtSY5IpQDxju9DA4Kq9nLwJVI4gvKf3HUQxllZfHC7JNqX2so0d%2FLeWUsJxtfjE5uhgkVD8Ty7F3z3MZ3%2FFCRpEof%2B84nKmZx1P9BhtVj99EKbgFAerPIgD3kCy2BW6i9JBUlO0tTyWJrCqm8UTJ0hS3LG4J6204IAnzDFIcen2yLzQn828F8smf0X2Fmith8%2BqcGIEGK2%2FfBfED6PcA%2BhybZbHtRsmXmoIiY0aZocRXKPyIAdJKrWNjuKrWoHiWr0shKTPHyOTu%2FMjaJ0NcqGBilu7vj%2BHaUjUFHoSen%2BjhCAfrViu%2B3ZCruK5RGcphfEWafCJM7mnMpIGM0GdMGsuERoZw9CHEHxazf6ufFSGXo5%2BSglSSzYya5pzHYroWAqOlOF%2BRCOiM015kqxgWMida4R5y524U7ACTuNYw7QbELu1E%2FHZEiHdNbOrphVgVS1g9hAaXZtNfIw7OMjj66RBtQ4U5IbZzmlvhaOGNAiNg5HVKA%2FzHwUWM%2Bknuu6criisQhLmslztHDW9OVmtZzMYiqnhVy%2Fo2J8HURe7AUV%2BYaCHwfABQs28dLzXeKB%2B%2B4sPiQbzf0yC1dntjFDGMQKYRBMsnXolrFSLNB5fY6Leo5xZJqCp2JW9ejQ38Bt61JtWHBuYrGbegp1PLDnLjvaO%2FYsvN%2FCxLZec1aUvxX8iUTzJyvJdgJ%2FdtpGzOLQ7vFp5vYytenC2OZRoBjuHKlA5yGztQcIGF3X8qlPwrgTC%2FLdXr25eR4um8KqSxTssmGuVfvQI%2F9rFoRt9tz3jM7QkLAmt4qm87Dg9UBK87B1yR%2BZJNZld0H60a45LNfTGraMdWdcWMDAwJ5Hld3kqlwS9tRrdcKt%2B2uUWquOKZo%2FORaPVszktvVw%2BUSNY9UJUnVWNlGwcVQHYOBAK0ID7dN0tqwgYKBWm2eAeKn5mshae1%2FDPZGdaR%2B1Y2DgCfFnY%2BBKMv7UIK6qmy3509IwYM%2BGGeHu2FMUMpDEkOyZVE%2FUWiIL7pFgruYWbS9ZoMGgj46YMlTIjCzqSK3ZuJbqyKwNFG5YFN%2BdOuJaWgLV0SRcOX9c%2F7ghz%2F1SQhiuB2Pglvl2jooGgnhEhxqIbyHBZL1O5sA8EqXgNx9H0C%2ByApHHrCZAVq0tT7IOBQQnjsoutJ8shgUmaBXU1rDAfWiWaMOiDTDB%2FgnPDbhTrvIBtT7htyV36tDtsRrOMuiOO4Vk8tibyJV%2F3STzfF5M6GfTiwzHBHv66HU3no3%2F%2FTTtaa1TYhvkl7iZNSCoGJfQvUXVhrzf%2Fs2%2Fh3VWLliS6CwNVBVvpzkcrbMAsElOKDitorH6eAbuZO%2Bs7wd3gqQ0NpSWFrWIMgvu5Idr%2Fvzvr6%2BTcO38x33x9%2BLb1%2BjbaysaDaB78w2jzLo9XS7WNGABctt8tA2we03npjaZjIkHxty73rJvjKlBTdfWoNsanHzIjTHj92%2Bufmqb%2Bfev69nC%2B%2FHxn9eWytSYR0Yg2s45aMX4pnfBvecnEclqvUxGic53A6%2Fp5bn3AC%2BdfKL8Rsmqjf2Ng8Vlxjl4HO06SJd3ppGa%2Bxi7fnRoW7roM6bbS0CEmB54Vl5nsve40drxTwxsi%2Fun99r%2FOHbEpzSevCqa8tclhZa16pd03KGe%2FduiWfSvNFC94Df3YoSNImY9NDi8SLWfEqMytUZ9RMmNm%2F4ewArKXRAmS1A9%2FyEdMEJZKMqAhUfvlvb1KivC7M598r2U%2FYkd3Ek5P4gpyVJOucTKYfp0QAfTBEABIYzJoAM7rQtnS3dGh1ZIQaVF%2BaCPoYw1bJb8jJEyVtTc8ei4lWQfr0li%2BIFDui1EO75GCdyJYw0I87l2MI8DtZ8c%2FsKJXCfRBOmS5HfZsEdgXbi5CLuOLoGLsOtoMrkIu8746vomUfZzL1oHfnK6ywd3d6XP4BO08Qk0aI0QaxgWZsz3QajwHjo3RvUajsQpSFnCjajSDRPujZxbb%2BnFSQwwTUzA0pt56bAr8tRXXrTla5mcAKiyyX%2FndwFadWEc6QKUzH9h7Okz0Tibfrny4vUlTS0tP7hRreqPd8jPyokfqYh3hYiv3DDx%2Fakol9KN1GpNKXSU2Ph5pTyHpbDr1veJ2vo%2BwwHTwL8jarzAAJyE3oOp52vqmRlqnrb%2Bwby%2BRB%2Bv3Y%2FTt0r4Vjf%2FWqwme2DDLlRIoj6SWfxJxKCGXiILlMmmwWodBg%2BOH7tilciAKbLOeDK1L1NrQEKGaEMCRc9tQNgnL%2BNIY7Sf84P4mBLOylh1vgX7EvgC8sxQtWFlEDJErnRgkoQ1GPqgq%2F%2B0koj7WPVwDlGyeALGAbqB20UUNlg%2Fgmr7EboLKZgU4FrH%2BBxm%2B5bWhth6VbYMEx0Sp7aTgbmK4D6%2FUc7hn9g2gMpXbOhBNxXJESiiR4ahw3vJNgCUSbF6iilB9eaZ35bhelmOj%2B5oXrqJ0wmBvfSjrPhYJlSvltpDhsqw9NxQPeZTb1VkeWxiT0VmRWMonNJ6%2B%2FhKElsMZ3QTHgB1OEcMJQS2GPZetbbF5G0YUOO4%2FToRiMX7YO7Sb%2Fwf%3C%2Fdiagram%3E%3C%2Fmxfile%3E) </p></font>

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

### Validação com Usuário - Presencial

**Vídeo 7** - Validação dos casos de uso com usuário por [Gabriel Lopes](https://github.com/BrzGab)

<p style="text-align: center"><iframe width="560" height="315" src="https://youtube.com/embed/Uhc9kiiB8rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>

<p style="text-align: center"><a href="https://www.youtube.com/watch?v=Uhc9kiiB8rA" target="_blank">Clique aqui para assistir no YouTube</a></p>

| **Nome** | **Função** | **Data** | **Hora** |
|:---------:|:------------------------:|:--------:|:--------:|
| [Gabriel Lopes](https://github.com/BrzGab) | Elaborador dos casos de uso | 01/06/2025 | 19:30 |
| João Vitor Alves Viana | Cidadão | 26/06/2025 | 13:30 |

## Termo de consentimento de imagem 
Este documento confirma que a(o) cidadão **João Vitor Alves Viana** forneceu seu consentimento formal para o uso de sua imagem, conforme os termos estabelecidos.

O termo foi assinado e encontra-se disponível no seguinte arquivo: [PDF](https://drive.google.com/file/d/12b8VxisovXvTVVNVnkFhr8HfvocugJdL/view?usp=sharing)

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
| 2.5    | Adicionando generalização no diagrama | [Gabriel Lopes](https://github.com/BrzGab)|17/05/2025| [Luiza da Silva Pugas](https://github.com/Luizaxx) | 07/07/2025 |

