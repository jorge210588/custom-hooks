# useForm Hook

Ejemplo de uso
```
    const initialForm = {
        name: "",
        age:0,
        email:""
    }
    const [formValues, handleInputChange, Reset] = useForm(initialForm);
```

useForm() //recibe estado inicial del formulario