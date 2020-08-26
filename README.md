
Projenin çalışabilmesi için öncelikle veri tabanı ekliyoruz.
Visual Studio programında ki menüden Tools > NuGet Package Maneger > Package Manager Console açıyoruz.

Açılan sayfaya login için;
"add-migration init -context LoginDbContext" ekliyoruz. (init ismini istediğiniz gibi değiştirebilirsiniz)
" update-database -context LoginDbContext" güncelleyerek veri tabanını ekliyoruz.

Versiye defteri için;
"add-migration init -context BookDbContext" ekliyoruz. (init ismini istediğiniz gibi değiştirebilirsiniz)
" update-database -context LoginDbContext" güncelleyerek veri tabanını ekliyoruz.

F5 veya Debug > Start Debugging tıklayarak projeyi çalıştırıyoruz.

