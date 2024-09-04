<!-- 
##posts
##users
##Category 
 -->"# laravel9blog" 
 <!-- para que sirva el slug tiene que estar el plugin jQuery-Plugin-stringToSlug-1.3 en public/vendor 
 DESPUES PONER
    <script src="{{asset('vendor/jQuery-Plugin-stringToSlug-1.3/jquery.stringToSlug.min.js')}}"></script>
   <script>
        $(document).ready(function() {
            $('#name').stringToSlug({
                setEvents: 'keyup keydown blur',
                getPut: '#slug',
                space:'-'
            });
        });
    </script>
 -->


 <!-- php artisan make:controller Admin/CategoryController --model=Category -r

De esa forma crea el controlador, y le asigna el modelo Category, entonces ya incluye al modelo y lo define como el tipo de variable de en los parámetros de las funciones -->
