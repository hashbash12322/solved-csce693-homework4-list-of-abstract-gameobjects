Download Link: https://assignmentchef.com/product/solved-csce693-homework4-list-of-abstract-gameobjects
<br>
<ol>

 <li> Create a list (e.g., std::vector) of abstract GameObjects that the Game class manages and executes. A game object should call both update() and render() using this list.  Redesign the existing GameObject class to be abstract as discussed in class.</li>

</ol>

When the list is deleted it should delete all of its’ “contained” GameObjects (hint: store std::unique_ptr&lt;&gt;() to manage a concrete GameObject’s lifetimes).

<ol start="2">

 <li>Create 3 concrete subclasses of the abstract GameObject to represent a Tank, Chopper and Pacman. Each of these subclasses should (upon creation) load the image associated with it (Tank -&gt; “tank-big-down.png”, Chopper -&gt; “choppersingle.png” and Pacman -&gt; “pacman_32x32.png”) which is stored in the assets/images folder.</li>

</ol>