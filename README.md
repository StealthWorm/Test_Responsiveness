<h1 style="
   display: flex;
   alignItems: center;
   justify-content: center;
   color: #7159c1"
>
   RESPONSIVIDADE
</h1>

<div style="
   font-size: 62.5%;
   border: 1px solid #7159c1;
   border-radius: 5px;
   font-size: 1rem;
   "
>
   <div style="
      font-size: 2rem;
      background-color: #7159c1; 
      border-radius: 5px 5px 0 0; 
      alignItems: center;
      justify-content: center;
      display: flex;
      color: #fff;
      "
 
   ## CSS Units
   </div>

   Unidades de medidas do CSS
   Layout Fixo
   `px` - Pixels

   Layout Fluido
   `%` - Porcentagem
   `auto` - Automática
   `vh` - Viewport Height (é o display)
   `vw` - Viewport Width (é o display)

   Textos Fixos
   1px  = 0.75pt
   16px = 12pt 

   Textos Fluidos
   `em`  - multiplicado pelo valor do pai na hierarquia. Se o container for o pai e tiver um font-size de 14px e o filho um font-size de 1em, seria como se estivesse multiplicando 1 x 14

   `rem` - multiplicado pelo root, que no caso seria o html body. Se o font-size padrão do html for 16px, então seria multiplicado por esse valor

   <div style="
      font-size: 2rem;
      background-color: #7159c1; 
      alignItems: center;
      justify-content: center;
      display: flex;
      color: #fff;
      "

   ## CSS Media Queries
   </div>

   ```CSS
   @media (max-width: 320px) {
      #form h3 {
         font-size: 2rem;  
      }]
   }
   ```

   <div style="
      font-size: 2rem;
      background-color: #7159c1; 
      alignItems: center;
      justify-content: center;
      display: flex;
      color: #fff;
      "

   ## HTML Media Attrib.
   </div>

   ```CSS
   <link 
      rel="stylesheet" 
      href="responsive.css" 
      media="screen and (max-width: 768px)"
   />
   ```

   <div style="
      font-size: 2rem;
      background-color: #7159c1; 
      alignItems: center;
      justify-content: center;
      display: flex;
      color: #fff;
      "

   ## Imagens
   </div>

   `<picture>`
   ```CSS
   <picture class="image" alt="Imagem">
      <source media="(min-width: 768px)" srcset="https://i.ytimg.com/vi/GykTLqODQuU/maxresdefault.jpg">
      <source media="(min-width: 320px)" srcset="https://i.ytimg.com/vi/GykTLqODQuU/hqdefault.jpg">
      <source media="(min-width: 10px)" srcset="https://i.ytimg.com/vi/GykTLqODQuU/mqdefault.jpg">
   ```

   ### JPG, PNG vs SVG
   > sempre que possível, utilize svg para manter a qualidade ao redimensionar

</div>












