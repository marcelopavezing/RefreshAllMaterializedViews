<h3>Funcion que refresca las vistas materilizadas en PostgreSQL.</h3>

Para refrescar los datos de las vistas materializadas en el schema public:

<code>select RefreshAllMaterializedViews();</code>


Para refrescar las vistas materializadas en otro schema:

<code>select RefreshAllMaterializedViews('my_schema');</code>
