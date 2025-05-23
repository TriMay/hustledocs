<div id="page_main"></div>


<script>

let data = {
    version: "1.9.20",
    updated: "2024-10-08",
    name: "CodexAchievementList",
    inherits: "Reference",
    script_path: "",
    scene_path: "",
    desc: "",
    signals: [
    ],
    constants: [
    ],
    properties: [
        { name:'achievements',
          type:'Dictionary', value:'{}',
                desc:"" },
        { name:'counters',
          type:'Dictionary', value:'{}',
                desc:"" },
        { name:'default_locked_title',
          type:'String', value:'""',
                desc:"" },
        { name:'default_locked_desc',
          type:'String', value:'""',
                desc:"" },
        { name:'default_locked_icon',
          type:'Variant', value:'null',
                desc:"" },
        { name:'default_unlocked_icon',
          type:'Variant', value:'null',
                desc:"" },
        { name:'uses_default_fanfare',
          type:'bool', value:'true',
                desc:"" },
        { name:'uses_default_sound',
          type:'bool', value:'true',
                desc:"" },
    ],
    methods: [
        { name:'define',
          params:['achievement_id:String', 'data:Dictionary'],
                desc:"" },
        { name:'set_title',
          params:['achievement_id:String', 'title:String'],
                desc:"" },
        { name:'set_desc',
          params:['achievement_id:String', 'desc:String'],
                desc:"" },
        { name:'set_icon',
          params:['achievement_id:String', 'icon'],
                desc:"" },
        { name:'set_locked_title',
          params:['achievement_id:String', 'title:String'],
                desc:"" },
        { name:'set_locked_desc',
          params:['achievement_id:String', 'desc:String'],
                desc:"" },
        { name:'set_locked_icon',
          params:['achievement_id:String', 'icon'],
                desc:"" },
        { name:'set_default_locked_title',
          params:['title:String'],
                desc:"" },
        { name:'set_default_locked_desc',
          params:['desc:String'],
                desc:"" },
        { name:'set_default_locked_icon',
          params:['icon'],
                desc:"" },
        { name:'mark_secret',
          params:['achievement_id:String', 'secret:bool=true'],
                desc:"" },
        { name:'mark_unlocked',
          params:['achievement_id:String', 'unlocked:bool=true'],
                desc:"" },
        { name:'is_secret',
          params:['achievement_id:String'], type:'bool',
                desc:"" },
        { name:'is_unlocked',
          params:['achievement_id:String'], type:'bool',
                desc:"" },
        { name:'is_array_unlocked',
          params:['achievements:Array'], type:'bool',
                desc:"" },
        { name:'assign_counter',
          params:['achievement_id:String', 'counter_id:String', 'target_value:int=-1'],
                desc:"" },
        { name:'get_counter_value',
          params:['counter_id:String'], type:'int',
                desc:"" },
        { name:'set_counter_value',
          params:['counter_id:String', 'value:int'],
                desc:"" },
        { name:'is_target_met',
          params:['achievement_id:String'], type:'bool',
                desc:"" },
        { name:'get_totals',
          params:[], type:'Dictionary',
                desc:"" },
        { name:'get_unlocked_array',
          params:[], type:'Array',
                desc:"" },
        { name:'get_display_title',
          params:['achievement_id:String'], type:'String',
                desc:"" },
        { name:'get_display_desc',
          params:['achievement_id:String'], type:'String',
                desc:"" },
        { name:'get_display_icon',
          params:['achievement_id:String'], type:'Texture',
                desc:"" },
        { name:'get_display_highlight',
          params:['achievement_id:String', 'ignore_locked_check:bool=false'], type:'Color',
                desc:"" },
        { name:'get_debug_title',
          params:['achievement_id:String', 'as_unlocked:bool=true'], type:'String',
                desc:"" },
        { name:'get_debug_desc',
          params:['achievement_id:String', 'as_unlocked:bool=true'], type:'String',
                desc:"" },
        { name:'get_debug_icon',
          params:['achievement_id:String', 'as_unlocked:bool=true'], type:'Texture',
                desc:"" },
        { name:'get_debug_highlight',
          params:['achievement_id:String', 'as_unlocked:bool=true'], type:'Color',
                desc:"" },
        { name:'get_display_counter_value',
          params:['achievement_id:String'], type:'int',
                desc:"" },
        { name:'get_display_counter_target',
          params:['achievement_id:String'], type:'int',
                desc:"" },
        { name:'get_display_counter_text',
          params:['achievement_id:String'], type:'String',
                desc:"" },
        { name:'__parse_to_texture',
          params:['input'], type:'Texture',
                desc:"" },
    ],
};


    Vue.createApp(ClassDocsComponent, data).mount("#page_main");
</script>