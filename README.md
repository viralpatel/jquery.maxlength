JQuery Maxlength
=================

A simple jquery plugin to set maxlength for a textarea and restrict text input.

*Read tutorial: [jQuery Maxlength](http://viralpatel.net/blogs/set-maxlength-of-textarea-input-using-jquery-javascript/).*


Usage
-----

### Step 1. Include Maxlength plugin script

	<script language="javascript" src="jquery.maxlength.js"></script>

### Step 2. Add `maxlength` attribute to &lt;textarea&gt;
	
	<textarea maxlength="35" 
		rows="5" cols="30" name="address"></textarea>
		
### Step 3. Initialize plugin

	<script type="text/javascript">
		$(document).ready(function($) {
				 //Set maxlength of all the textarea (call plugin)
				 $().maxlength();
		})
	</script>
		
		
License
-------		

	Copyright 2013 Viral Patel and other contributors
	http://viralpatel.net

	Permission is hereby granted, free of charge, to any person obtaining
	a copy of this software and associated documentation files (the
	"Software"), to deal in the Software without restriction, including
	without limitation the rights to use, copy, modify, merge, publish,
	distribute, sublicense, and/or sell copies of the Software, and to
	permit persons to whom the Software is furnished to do so, subject to
	the following conditions:

	The above copyright notice and this permission notice shall be
	included in all copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
	EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
	MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
	NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
	LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
	OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
	WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.