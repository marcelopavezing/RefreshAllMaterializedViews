Para refrescar las vistas materializadas en el schema public:

select RefreshAllMaterializedViews();


Para refrescar las vistas materializadas en otro schema:

select RefreshAllMaterializedViews('my_schema');
