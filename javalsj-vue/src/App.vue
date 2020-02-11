    <template>
      <div>
    		<h2>Button Size</h2>
    		<p>Small Buttons</p>
    		<LinkButton iconCls="icon-add">Add</LinkButton>
    		<LinkButton iconCls="icon-remove">Remove</LinkButton>
    		<LinkButton iconCls="icon-save">Save</LinkButton>
    		<LinkButton iconCls="icon-cut" :disabled="true">Cut</LinkButton>
    		<p>Large Buttons</p>
    		<LinkButton iconCls="icon-large-Picture2_1" size="large" iconAlign="top">Picture</LinkButton>
    		<LinkButton iconCls="icon-large-Picture2_2" size="large" iconAlign="top">Clipart</LinkButton>
    		<LinkButton iconCls="icon-large-Picture2_3" size="large" iconAlign="top">Shapes</LinkButton>
    		<LinkButton iconCls="icon-large-Picture2_4" size="large" iconAlign="top">SmartArt</LinkButton>
    		<LinkButton iconCls="icon-large-chart" size="large" iconAlign="top">Chart</LinkButton>
      </div>
    </template>
     
    <script>
    export default {};
    </script>