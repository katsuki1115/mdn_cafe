export default{
	router: {
		extendRoutes(routes, resolve){
			routes.push({
				name: 'notFound',
				path: '*',
				component: resolve(__dirname, 'pages/index.vue')
			})
		}
	}
}