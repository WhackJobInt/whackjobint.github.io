## IfCanSee

<p>Conditional function which checks if pointer can be seen by the entity.</p>

<div class="admonition warning">
<p class="admonition-title">Catharsis Reborn Feature</p>
<p>The following function will only work in <b>Catharsis Reborn</b>.</p>
</div>

<h1>Syntax</h1>
<pre><code class="language-js">
IfCanSee "[target/caller/player] Block begin"
	// stub
Block end
</code></pre>

<div class="admonition note">
<p class="admonition-title">Note</p>
<p>This function doesn't support one line execution. It must have <b>Block begin</b> and <b>Block end</b>.</p>
</div>

<h1>Example</h1>
<pre><code class="language-js">
// This will check if Player is visible, and goes to a different pattern
pt_playercheck
{
	actions
	{
		TargetPlayer 1
		IfCanSee "target Block begin"
			Pattern pt_playersee
			Return 1
		Block end
		
		Pattern pt_playercheckagain
	}
}
</code></pre>