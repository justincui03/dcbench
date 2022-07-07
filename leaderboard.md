---
layout: page
title: Leaderboard
permalink: /leaderboard/
---
<link rel="stylesheet" href="https://cdn.datatables.net/1.10.21/css/jquery.dataTables.min.css">
<link rel="stylesheet" href="../css/main.css" />
<script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/1.10.21/js/jquery.dataTables.min.js"></script>



<div id="leaderboard" class="container button-list">
  <a class="button" href="#div_cifar10_ipc1_heading">CIFAR-10 IPC1</a>
  <a class="button" href="#div_cifar10_ipc10_heading">CIFAR-10 IPC10</a>
  <a class="button" href="#div_cifar10_ipc50_heading">CIFAR-10 IPC50</a>
</div>
<div id="leaderboard" class="container button-list">
  <a class="button" href="#div_cifar100_ipc1_heading">CIFAR-100 IPC1</a>
  <a class="button" href="#div_cifar100_ipc10_heading">CIFAR-100 IPC10</a>
  <a class="button" href="#div_cifar100_ipc50_heading">CIFAR-100 IPC50</a>
</div>
<div id="leaderboard" class="container button-list">
  <a class="button" href="#div_tinyimagenet_ipc1_heading">TinyImagenet IPC1</a>
  <a class="button" href="#div_tinyimagenet_ipc10_heading">TinyImagenet IPC10</a>
  <a class="button" href="#div_tinyimagenet_ipc50_heading">TinyImagenet IPC50</a>
</div>

<section class="container" id="div_cifar10_ipc1_heading">
  <div class="heading">
    <p>
    CIFAR10 IPC 1
    </p>
  </div>
  <div id="div_cifar10_ipc1"></div>
</section>

<section class="container" id="div_cifar10_ipc10_heading">
  <div class="heading">
    <p>
    CIFAR10 IPC 10
    </p>
  </div>
  <div id="div_cifar10_ipc10"></div>
</section>

<section class="container" id="div_cifar10_ipc50_heading">
  <div class="heading">
    <p>
    CIFAR10 IPC 50
    </p>
  </div>
  <div id="div_cifar10_ipc50"></div>
</section>

<section class="container" id="div_cifar100_ipc1_heading">
  <div class="heading">
    <p>
    CIFAR100 IPC 1
    </p>
  </div>
  <div id="div_cifar100_ipc1"></div>
</section>

<section class="container" id="div_cifar100_ipc10_heading">
  <div class="heading">
    <p>
    CIFAR100 IPC 10
    </p>
  </div>
  <div id="div_cifar100_ipc10"></div>
</section>

<section class="container" id="div_cifar100_ipc50_heading">
  <div class="heading">
    <p>
    CIFAR100 IPC 50
    </p>
  </div>
  <div id="div_cifar100_ipc50"></div>
</section>

<section class="container" id="div_tinyimagenet_ipc1_heading">
  <div class="heading">
    <p>
    TinyImagenet IPC 1
    </p>
  </div>
  <div id="div_tinyimagenet_ipc1"></div>
</section>

<section class="container" id="div_tinyimagenet_ipc10_heading">
  <div class="heading">
    <p>
    TinyImagenet IPC 10
    </p>
  </div>
  <div id="div_tinyimagenet_ipc10"></div>
</section>

<section class="container" id="div_tinyimagenet_ipc50_heading">
  <div class="heading">
    <p>
    TinyImagenet IPC 50
    </p>
  </div>
  <div id="div_tinyimagenet_ipc50"></div>
</section>

<script>
    $("#div_cifar10_ipc1").load("../tables/cifar10-ipc1.html", function() {
      $('#cifar10-ipc1').DataTable();
    });
    $("#div_cifar10_ipc10").load("../tables/cifar10-ipc10.html", function() {
      $('#cifar10-ipc10').DataTable();
    });
    $("#div_cifar10_ipc50").load("../tables/cifar10-ipc50.html", function() {
      $('#cifar10-ipc50').DataTable();
    });
    $("#div_cifar100_ipc1").load("../tables/cifar100-ipc1.html", function() {
      $('#cifar10-ipc1').DataTable();
    });
    $("#div_cifar100_ipc10").load("../tables/cifar100-ipc10.html", function() {
      $('#cifar10-ipc10').DataTable();
    });
    $("#div_cifar100_ipc50").load("../tables/cifar100-ipc50.html", function() {
      $('#cifar10-ipc50').DataTable();
    });
    $("#div_tinyimagenet_ipc1").load("../tables/tinyimagenet-ipc1.html", function() {
      $('#tinyimagenet-ipc1').DataTable();
    });
    $("#div_tinyimagenet_ipc10").load("../tables/tinyimagenet-ipc10.html", function() {
      $('#tinyimagenet-ipc10').DataTable();
    });
    $("#div_tinyimagenet_ipc50").load("../tables/tinyimagenet-ipc50.html", function() {
      $('#tinyimagenet-ipc50').DataTable();
    });
</script>
<script>
    $(document).ready(function() {
    });
</script>



