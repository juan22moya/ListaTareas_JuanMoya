Se Usa el framework Yew V0.17.4, basado en Rust para desplegar una lista de tareas.
Con Funcionalidad, de ingresar, editar las tareas y su respectivo estado.

Para ejecutar la aplicación, se debe ingresar al directorio: examples/todomvc
y ejecutar: 
wasm-pack build --target web --out-name wasm --out-dir ./static && miniserve ./static --index index.html
