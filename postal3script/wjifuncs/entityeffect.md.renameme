## EntityEffect

<p>Sets, adds, or removes an entity's entity effect.</p>

<div class="admonition warning">
<p class="admonition-title">Catharsis Reborn Feature</p>
<p>The following function will only work in <b>Catharsis Reborn</b>.</p>
</div>

<pre><code class="language-js">
// from CR's ai_st_init.p3s
Const EF_NOSHADOW,0
Const EF_NODRAW,1
Const EF_NORECEIVESHADOW,2
Const EF_ITEM_BLINK,3
</code></pre>


<h1>Syntax</h1>
<p><code>EntityEffect [0 to 3],add</code> -- Adds the effect to this entity.</p>
<p><code>EntityEffect [0 to 3],remove</code> -- Removes the effect to this entity.</p>
<p><code>EntityEffect 0,clear</code> -- Clears all effects from this entity.</p>

<h1>Example</h1>
<pre><code class="language-js">
// This will make the NPC visible again
pt_default
{
	actions
	{
		EntityEffect EF_NODRAW,remove
	}
}
</code></pre>