# OpCMS
The folder Structure Proposed

[CMS]:
	[Libraries]: other open source code files (oauth2, ..)
		[oauth2]
		[..]

	[Core]: Created by the author
		[Controllers]: handling controllers action
			BaseController,  
		[Parsers]:  parsing functions(pre, post)
			PreProcessParser, PostProcessParser
		[Handlers]: handling exceptions errors, files, configurations etc
			ErrorHandler, ConfigHandler, RegistryHandler
		[Interceptors]: libraries files for intercepting program flow ie. loggers, db, etc. 
			LoggerInterceptor, DatabaseInterceptor, DBInterceptor
	Config:  Add entries to identify each components inside CMS
		Libraries
		Core
			Controllers
			Parsers
			Handlers
			Interceptors

Config: Add entries to identify each components in Root
	Bootstrap
	Plugins
	Personal
	..
	
[Bootstrap]:
	Twitter Bootstrap, etc.
	
[Plugins]:Open source world standard for plugins entry
	Config:Registering plugins to the main cms for desired actions.
		Add entries to identify each modules/plugins
		
[Personal]:	Personal plugins developed for the framework
	Config:Configuration handling for personal libraries and associations

