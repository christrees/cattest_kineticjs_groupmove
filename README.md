cattest_kineticjs_groupmove
===========================

Attempting to use kineticjs to move group.


    <!-- BEGIN cattest_uid -->
    <!-- author: cat@horseoff.com -->
    <!-- date: 20120704 -->
    <!-- uid: cattest_kineticjs_groupmove -->
    <!-- src: https://github.com/christrees/cattest_kineticjs_groupmove -->
    <!-- pub: http://cat.kineticjs_com.horseoff.com/2012/07/04/cattest_kineticjs_groupmove/kinetictest_groupmove.html -->
    <!-- info: http://cat.kineticjs_com.horseoff.com/2012/07/04/cattest_kineticjs_groupmove/README.md -->
    <!-- END cattest_uid -->


    <div id="cattest"><h3></h3>
        <p>-- intent: Attempting to use kineticjs to move group.</p>
        <p>-- bug: After moving the group, the event area does not move to the new location of the object image.</p>
        <h4>-- Reproduce Issue Steps:</h4>
        <ol>
            <li>Mouse over any animal and see hover glow.</li>
            <li>Notice animal positions.</li>
            <li>Now click PAN to enable group drag.</li>
            <li>Click on any group element and drag group +1in or so to new position.</li>
            <li>Now click LOCK to turn group drag off.</li>
            <li>Mouse over any animal and DO NOT see hover glow.</li>
            <li>Mouse over any animal ORIGINAL position and see hover glow.</li>
        </ol>
        <h4>-- Reference Links</h4>
        <ol>
            <li><a href="http://cat.kineticjs_com.horseoff.com/2012/07/04/cattest_kineticjs_groupmove/kinetictest_groupmove.html">pubref: Public Demo Testing the CAT Group Move.</a></li>
            <li><a href="https://github.com/christrees/cattest_kineticjs_groupmove">githubref: GitHub Repo.</a></li>
            <li><a href="http://www.html5canvastutorials.com/labs/html5-canvas-animals-on-the-beach-game-with-kineticjs/">parentref: The kineticjs Demo this is based on.</a></li>
            <li><a href="http://www.kineticjs.com/forum/viewtopic.php?f=8&t=826">pushref1: First place I linked a reference to this in kineticjs forum</a></li>
        </ol>
    </div>