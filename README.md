StringExtensions
================

Alguns metodos para estender as strings


	Console.WriteLine("".IsNullOrEmpty());//True
	Console.WriteLine("".IsNotNullOrEmpty());//False
	Console.WriteLine("{0} {1}".FormatWith("Cleyton","Ferrari"));//Cleyton Ferrari
	Console.WriteLine("".NullIfEmpty());//
	Console.WriteLine("Você é Cleyton Ferrari".ToSlug(16));//voce-e-cleyton-f
	Console.WriteLine("Cleyton Ferrari/Criando metodos".ToSlugWithSegments());//cleyton-ferrari/criando-metodos
	Console.WriteLine("CleytonFerrari".SeparatePascalCase());//Cleyton Ferrari
	Console.WriteLine("Cleyton Ferrari".SplitAndTrim(' ').First());//Cleyton
	Console.WriteLine("Cleyton Ferrari".Contains("Ferrari"));//True
	Console.WriteLine("Cleyton".Limit(5));//Cleyt
