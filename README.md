# poc-spring-web-mvc-fix
<!-- Se fixea la referencia del package para que el scan referencie a los controllers -->
	<context:component-scan
		base-package="carmelo.spring.webmvc" />
	<context:annotation-config />
