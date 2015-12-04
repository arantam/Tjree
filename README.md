# Tjree
A tree plugin created with jQuery, Bootstrap UI styled.
Lots of jQuery tree plugins found everywhere, but none of them meet my need. That's why this plugin says hello world.

Why this tree plugins named 'Tjree':
Because my name is 'Tanj', so 'Tanj'+"Tree'=Tjree. :p

What you can do with this tree plugin:
1. fold/unfold;
2. delete a node, edit a node, add a child, or see more info of the node;
3. drag and drop a node;

How to use:


var settings = {
        debugMode: false,
        debugInfoClass: 'debug_info',
        rootText: '根节点',
        reloadText: '正在重新加载...',
        treeClass: 'tree_list list-unstyled',
        nodeIdPrefix: 'tanj_tree_node_', // unique
        nodeStatusClassPrefix: 'node_status_',
        nodeClass: 'tree_node',
        nodeDeletedClass: 'deleted',
        nodeDivClass: 'node_content',
        nodeIconClass: 'node_icon',
        nodeNameClass: 'node_name',
        nodeBtnAreaClass: 'btn_area',
        nodeHoveredClass: 'hovered',
        nodeFocusedClass: 'focused',
        folderOpenClass: 'glyphicon-folder-open',
        folderCloseClass: 'glyphicon-folder-close',
        leafIconClass: 'glyphicon-file',
        nodeDragHoveredClass: 'dragHovered',
        nodeDraggedItemClass: 'draggedItem',
        tmpNodeClass: 'new',
        tmpTopClass: 'tmp_top',
        tmpBottomClass: 'tmp_bottom',
        buttons: {
            add: {
                url: '',
                callback: null // function(id, parentId)
            },
            del: {
                url: '',
                callback: null // function(id, parentId)
            },
            edit: {
                url: '',
                callback: null // function(id, parentId)
            },
            info: {
                callback: null // function(id, parentId)
            },
            dnd: { // drag and drop
                url: '',
                callback: null // function(id, parentId)
            }
        },
        widgets: {
            select: '',
            foldSwitch: false,
            buttons: false,
            dragAndDrop: false
        },
        animate: 100 // ms
    };



so far, this tree plugin just contains these simple functions as above or even hides some bugs, however, hope some ppl like it and help with improving it in future.

