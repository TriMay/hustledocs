<div id="page_main"></div>


<script>

let data = {
    version: "1.9.0",
    updated: "2024-04-03",
    name: "CodexStats",
    inherits: "Reference",
    script_path: "",
    scene_path: "",
    desc: "",
    signals: [
    ],
    constants: [
    ],
    properties: [
        { name:'max_health',
          type:'int', value:'1000',
                desc:"" },
        { name:'air_options',
          type:'int', value:'2',
                desc:"" },
        { name:'lose_option_in_neutral',
          type:'bool', value:'true',
                desc:"" },
        { name:'air_option_bar',
          type:'bool', value:'false',
                desc:"" },
        { name:'air_option_name',
          type:'String', value:'"Air Options"',
                desc:"" },
        { name:'free_cancels',
          type:'int', value:'2',
                desc:"" },
        { name:'damage_taken',
          type:'float', value:'1.0',
                desc:"" },
        { name:'knockback_taken',
          type:'float', value:'1.0',
                desc:"" },
        { name:'di_strength',
          type:'float', value:'1.0',
                desc:"" },
        { name:'gravity',
          type:'float', value:'0.5',
                desc:"" },
        { name:'friction_ground',
          type:'float', value:'2.5',
                desc:"" },
        { name:'friction_air',
          type:'float', value:'0.2',
                desc:"" },
        { name:'max_speed_ground',
          type:'float', value:'15.0',
                desc:"" },
        { name:'max_speed_air',
          type:'float', value:'13.0',
                desc:"" },
        { name:'max_speed_fall',
          type:'float', value:'8.0',
                desc:"" },
        { name:'hurtbox_x',
          type:'int', value:'0',
                desc:"" },
        { name:'hurtbox_y',
          type:'int', value:'-16',
                desc:"" },
        { name:'hurtbox_width',
          type:'int', value:'14',
                desc:"" },
        { name:'hurtbox_height',
          type:'int', value:'16',
                desc:"" },
        { name:'sprite_position',
          type:'Vector2', value:'Vector2()',
                desc:"" },
        { name:'sprite_scale',
          type:'Vector2', value:'Vector2()',
                desc:"" },
        { name:'sprite_texture',
          type:'Texture', value:'null',
                desc:"" },
    ],
    methods: [
        { name:'_init',
          params:['data=null'],
                desc:"" },
        { name:'define',
          params:['data=null'],
                desc:"" },
        { name:'duplicate',
          params:[], type:'CodexStats',
                desc:"" },
        { name:'copy_to',
          params:['copy'],
                desc:"" },
        { name:'parse_fighter',
          params:['char_instance:Fighter'],
                desc:"" },
        { name:'parse_dictionary',
          params:['data:Dictionary'],
                desc:"" },
    ],
};


    Vue.createApp(ClassDocsComponent, data).mount("#page_main");
</script>