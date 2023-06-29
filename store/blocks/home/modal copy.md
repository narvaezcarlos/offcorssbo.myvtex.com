{
	"modal-trigger#home": {
		"title":"modal home",
		"props": { 
			"trigger": "load-session"
			
	 },
		"children": ["modal-layout#home"]
	},
	"modal-layout#home": {
		"props": {
			"blockClass": "newsletter-modal-home",
			"fullScreen": true
		},
		"children": ["modal-header#home", "modal-content#home"]
	},
	"modal-header#home": {
		"props": {
			"showCloseButton": true,
			"blockClass": "newsletter-modal-home",
			"iconCloseSize": 34
		}
	},
	"modal-content#home": {
		"children": ["flex-layout.row#home"],
		"props": {
			"blockClass": "content-modal-home"
		}
	},
	"flex-layout.row#home": {
		"props": {
			"preventHorizontalStretch": true,
			"preserveLayoutOnMobile": false,
			"preventVerticalStretch": false,
			"colSizing": "equal",
			"blockClass": "row-home-form"
		},
		"children": [
			"flex-layout.col#content-suscribe",
			"flex-layout.col#content-home-form"
		]
	},
	"flex-layout.col#content-home-form": {
		"children": ["image#banner-modal"],
		"props": {
			"verticalAlign": "middle",
			"blockClass": "content-home-form"
		}
	},
	"image#banner-modal": {
		"props": {
			"src": "/arquivos/banner-modal-expectation-OffcorssInter-21.jpg",
			"alt": "home",
			"blockClass": "content-home-modalimage"
		}
	},
	"modal-trigger#size-chart": {
		"children": ["rich-text#btn-size-chart", "modal-layout#size-chart"]
	},
	"rich-text#btn-size-chart": {
		"props": {
			"text": "Size chart",
			"font": "t-heading-5",
			"blockClass": "btn-size-chart"
		}
	},
	"modal-layout#size-chart": {
		"props": {
			"blockClass": "modal-size-chart"
		},
		"children": ["modal-header#size-chart", "modal-content#size-chart"]
	},
	"modal-header#size-chart": {
		"props": {
			"showCloseButton": true,
			"blockClass": "newsletter-modal-home"
		}
	},
	"modal-content#size-chart": {
		"children": [
			"responsive-layout.desktop#desktop",
			"responsive-layout.mobile#mobile"
		],
		"props": {
			"blockClass": "content-modal-home"
		}
	},
	"responsive-layout.desktop#desktop": {
		"children": ["flex-layout.row#size-chart-desktop"]
	},
	"flex-layout.row#size-chart-desktop": {
		"props": {
			"preventHorizontalStretch": true,
			"preserveLayoutOnMobile": false,
			"preventVerticalStretch": false,
			"colSizing": "equal",
			"blockClass": "row-size-chart"
		},
		"children": ["flex-layout.col#content-size-chart-desktop"]
	},
	"flex-layout.col#content-size-chart-desktop": {
		"children": ["image#image-size-chart-desktop"],
		"props": {
			"verticalAlign": "middle",
			"blockClass": "content-size-chart"
		}
	},
	"image#image-size-chart-desktop": {
		"props": {
			"src": "/arquivos/size-chart-desktop.jpg",
			"alt": "Size chart"
		}
	},
	"responsive-layout.mobile#mobile": {
		"children": ["flex-layout.row#size-chart-mobile"]
	},
	"flex-layout.row#size-chart-mobile": {
		"props": {
			"preventHorizontalStretch": true,
			"preserveLayoutOnMobile": false,
			"preventVerticalStretch": false,
			"colSizing": "equal",
			"blockClass": "row-size-chart"
		},
		"children": ["flex-layout.col#content-size-chart-mobile"]
	},
	"flex-layout.col#content-size-chart-mobile": {
		"children": ["image#image-size-chart-mobile"],
		"props": {
			"verticalAlign": "middle",
			"blockClass": "content-size-chart"
		}
	},
	"image#image-size-chart-mobile": {
		"props": {
			"src": "/arquivos/size-chart-mobile.jpg",
			"alt": "Size chart"
		}
	}
}

*/
sliderRightArrow--slider__customPage

background: #D5D1CB;
border-radius: 50%;
margin: 5px;
padding: 5px;
color: white;
font-weight: 100; */