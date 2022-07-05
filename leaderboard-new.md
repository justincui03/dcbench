---
layout: page
title: Leaderboard
permalink: /leaderboard-new/
---
<link rel="stylesheet" href="https://cdn.datatables.net/1.10.21/css/jquery.dataTables.min.css">
<link rel="stylesheet" href="/css/main.css" />
<script type="text/javascript" src="https://code.jquery.com/jquery-3.5.1.js"></script>
<script type="text/javascript" src="https://cdn.datatables.net/1.10.21/js/jquery.dataTables.min.js"></script>



<div id="leaderboard" class="container button-list">
  <a class="button" href="#div_cifar10_Linf_heading">CIFAR-10 IPC1</a>
  <a class="button" href="#div_cifar10_L2_heading">CIFAR-10 IPC10</a>
  <a class="button" href="#div_cifar10_corruptions_heading">CIFAR-10 IPC50</a>
</div>
<div id="leaderboard" class="container button-list">
  <a class="button" href="#div_cifar100_Linf_heading">CIFAR-100 IPC1</a>
  <a class="button" href="#div_cifar100_corruptions_heading">CIFAR-100 IPC10</a>
  <a class="button" href="#div_imagenet_Linf_heading">CIFAR-100 IPC50</a>
</div>
<div id="leaderboard" class="container button-list">
  <a class="button" href="#div_imagenet_Linf_heading">TinyImagenet IPC1</a>
  <a class="button" href="#div_imagenet_Linf_heading">TinyImagenet IPC10</a>
  <a class="button" href="#div_imagenet_Linf_heading">TinyImagenet IPC50</a>
</div>

<section class="container" id="div_cifar10_Linf_heading">
  <div class="heading">
    <p>
    CIFAR10 IPC 1
    </p>
  </div>
  <div id="div_cifar10_Linf"></div>
</section>

<script>
    $("#div_cifar10_Linf").load("/tables/cifar10-ipc1.html");

    $(document).ready(function () {
      $("#cifar10_leaderboard_Linf").DataTable();
    });
</script>



