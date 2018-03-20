# Flip Card Effect using Css3

#CSS CODE

<pre><code>
  .flip-container {
				-webkit-perspective: 1000;
				-moz-perspective: 1000;
				-o-perspective: 1000;
				perspective: 1000;
				border: 1px solid #ccc;
			}

			.flip-container:hover .flipper{	
				-webkit-transform: rotateY(180deg);
				-moz-transform: rotateY(180deg);
				-o-transform: rotateY(180deg);
				transform: rotateY(180deg);
			}

			.flip-container, .front, .back {
				width: 320px;
				height: 427px;
			}

			.flipper {
				-webkit-transition: 0.6s;
				-webkit-transform-style: preserve-3d;
				-moz-transition: 0.6s;
				-moz-transform-style: preserve-3d;
				-o-transition: 0.6s;
				-o-transform-style: preserve-3d;
				transition: 0.6s;
				transform-style: preserve-3d;
				position: relative;
			}

			.front, .back {
				-webkit-backface-visibility: hidden;
				-moz-backface-visibility: hidden;
				-o-backface-visibility: hidden;
				backface-visibility: hidden;
				position: absolute;
				top: 0;
				left: 0;
			}
			
			.front {
				background: url('137646854.jpg') 0 0 no-repeat;
				z-index: 2;
			}

			.back {
				background: url('137646854.jpg') 0 0 no-repeat;
				-webkit-transform: rotateY(180deg);
				-moz-transform: rotateY(180deg);
				-o-transform: rotateY(180deg);
				transform: rotateY(180deg);
				background: #af8f66;
			}

			.front .name {
				font-size: 2em;
				display: inline-block;
				background: rgba(33, 33, 33, 0.9);
				color: #f8f8f8;
				font-family: Courier;
				padding: 5px 10px;
				border-radius: 5px;
				bottom: 60px;
				left: 25%;
				position: absolute;
				text-shadow: 0.1em 0.1em 0.05em #333;

				-webkit-transform: rotate(-20deg);
				-moz-transform: rotate(-20deg);
			  -o-transform: rotate(-20deg);
				transform: rotate(-20deg);
			}
</code></per>


#Preview
<>
