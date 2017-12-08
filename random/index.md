---
title: Archivio della Randomicità
read_time: false
comments: false
---

<div>
  <style>
    #mmb_pswitch,
    #mmb_pswitch_gfx,
    .mmb_coin,
    .mmb_block {
        user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        -o-user-select: none;
        -webkit-user-select: none;
    }
    #mmb_pswitch {
        display: none;
    }
    #mmb_pswitch_gfx {
        vertical-align: middle;
        cursor: pointer;
        display: inline-block;
        width: 16px;
        height: 18px;
    }
    #mmb_pswitch + #mmb_pswitch_gfx {
        background: url('http://i.imgur.com/40nmlmK.png') no-repeat;
        background-position: -16px -14px;
    }
    #mmb_pswitch:checked + #mmb_pswitch_gfx {
        background: url('http://i.imgur.com/40nmlmK.png') no-repeat;
        background-position: -16px 4px;
    }
    .mmb_block,
    .mmb_coin {
        vertical-align: middle;
        display: inline-block;
        width: 16px;
        height: 16px;
    }
    #mmb_pswitch ~ .mmb_block,
    #mmb_pswitch:checked ~ .mmb_coin {
        background: url('http://i.imgur.com/40nmlmK.png') no-repeat;
        background-position: 0px 0px;
    }
    #mmb_pswitch:checked ~ .mmb_block,
    #mmb_pswitch ~ .mmb_coin {
        background: url('http://i.imgur.com/40nmlmK.png') no-repeat;
        background-position: 0px -16px;
    }
  </style>
  <input type="checkbox" id="mmb_pswitch"><label for="mmb_pswitch" id="mmb_pswitch_gfx"></label>
  <br />
  <span class="mmb_block"></span><span class="mmb_block"></span><span class="mmb_coin"></span><span class="mmb_coin"></span><span class="mmb_block"></span><span class="mmb_block"></span><br />
</div>
<p id="p"></p>
<script>
var id1 = document.getElementById('id1'); var id2 = $( '#id' );
if (id1.checked = true) {
  $( '#p' ).html = "lol"
}
</script>
