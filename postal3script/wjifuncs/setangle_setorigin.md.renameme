# Angle and Position functions

## SetAngle

<p>Sets, adds, or subtracts from an entity's absolute angle.</p>

<div class="admonition warning">
<p class="admonition-title">Catharsis Reborn Feature</p>
<p>The following function will only work in <b>Catharsis Reborn</b>.</p>
</div>

<h1>Syntax</h1>
<p><code>SetAngle [angle]</code> -- Sets the entity's angle to this fixed value.</p>
<p><code>SetAngle [angle],add</code> -- Adds more value to this entity's angle.</p>
<p><code>SetAngle [angle],sub</code> -- Subtracts value from this entity's angle.</p>

<div class="admonition warning">
<p class="admonition-title">TODO</p>
<p>This function might have more parameters in the future.</p>
</div>

<h1>Example</h1>
<pre><code class="language-js">
// This will make the NPC rotate itself every one second
pt_default
{
	actions
	{
		Wait 1.0
		SetAngle 5,add
		Repeat 0
	}
}
</code></pre>

<br>
## SetOrigin

<p>Sets an entity's absolute position.</p>

<div class="admonition warning">
<p class="admonition-title">Catharsis Reborn Feature</p>
<p>The following function will only work in <b>Catharsis Reborn</b>.</p>
</div>

<h1>Syntax</h1>
<p><code>SetOrigin [pointer],[x],[y],[z]</code> -- Sets the entity's position to this position.</p>
<p><code>SetOrigin [pointer],[pointer2]</code> -- Sets the entity's position to that entity's position.</p>

<h1>Example</h1>
<pre><code class="language-js">
// This will make the NPC teleport to the player on execution
pt_swooshtoplayer
{
	actions
	{
		TargetPlayer 1
		SetOrigin self,target
	}
}

// This however will make the NPC chain the Player to themselves endlessly
pt_cantescape
{
	actions
	{
		TargetPlayer 1
		SetOrigin target,self
		Wait 3
		Repeat 0
	}
}

// This makes the NPC teleport to a fixed position
pt_tele
{
	actions
	{
		SetOrigin self,423,-231,831
		Pattern pt_surprise
	}
}
</code></pre>