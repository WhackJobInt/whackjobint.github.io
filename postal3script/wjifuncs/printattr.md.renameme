## PrintAttr

<p>Prints out the value of an attribute to the console. For debugging purposes only.</p>

<div class="admonition warning">
<p class="admonition-title">Catharsis Reborn Feature</p>
<p>The following function will only work in <b>Catharsis Reborn</b>.</p>
</div>

<h1>Syntax</h1>
<p><code>PrintAttr [attr_name]</code> -- Prints out this attribute's value to the console.</p>

<div class="admonition note">
<p class="admonition-title">Note</p>
<p>For this function you need to have <b>developer 1</b> enabled.</p>
</div>

<h1>Example</h1>
<pre><code class="language-js">
// This will print out the health of the entity to console.
pt_default
{
	actions
	{
		PrintAttr "ea_health"
	}
}

// PrintAttr can be used in many other ways aswell
pt_default
{
	actions
	{
		IfAttr "ea_health < 25 Block begin"
			PrintAttr "I_have_less_than_25_health"
		Block end
	}
}
</code></pre>