# nachopsosa
tarea
digraph Organigrama_Zoologico {
    node [shape=box, style=rounded];
    Administrador_del_Zoologico -> Jefe_de_Operaciones;
    Jefe_de_Operaciones -> Encargado_de_Alimentacion_y_Cuidado_de_Animales;
    Encargado_de_Alimentacion_y_Cuidado_de_Animales -> Supervisor_de_Alimentacion_y_Cuidado_de_Animales;
    Supervisor_de_Alimentacion_y_Cuidado_de_Animales -> Empleados_de_Alimentacion_y_Cuidado_de_Animales [label="3x"];
    Encargado_de_Alimentacion_y_Cuidado_de_Animales -> Veterinario;
    Jefe_de_Operaciones -> Encargado_de_Mantenimiento;
    Encargado_de_Mantenimiento -> Supervisor_de_Mantenimiento;
    Supervisor_de_Mantenimiento -> Personal_de_Mantenimiento [label="2x"];
    Jefe_de_Operaciones -> Encargado_de_Servicios_Generales;
    Encargado_de_Servicios_Generales -> Supervisor_de_Servicios_Generales;
    Supervisor_de_Servicios_Generales -> Personal_de_Servicios_Generales [label="1x"];
    Administrador_del_Zoologico -> Jefe_de_Administracion_y_Finanzas;
    Jefe_de_Administracion_y_Finanzas -> Encargado_de_Finanzas;
    Encargado_de_Finanzas -> Contador [label="1x"];
    Jefe_de_Administracion_y_Finanzas -> Encargado_de_Recursos_Humanos;
    Encargado_de_Recursos_Humanos -> Responsable_de_Recursos_Humanos [label="1x"];
}
