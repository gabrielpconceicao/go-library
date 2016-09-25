# go-library
Simple js library to control the dom elements

Usage examples

<pre>
gO.ready( function(){
	var divElement = gO.el( 'div' )
		.atr( 'data-title', 'example' )
		.addCls( 'hidden' )
		.val( 'Html example' );

	gO.elCreate( 'input' )
		.atr( 'name', 'example' )
		.val( 'Input example' )
		.show( divElement );
});
</pre>


#Documentation

http://www.gabrielconceicao.com/go
