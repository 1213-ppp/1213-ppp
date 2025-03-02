<div>
    <div class="po" onclick="pol(po)"></div>
    <script>
        let i = '<pclass="pold">','?','</p>';
        function pol(po) {
            po.innerHTML += i
        }
        pol(po);
    </script>
    <style>
        .po {
            width: 3em;
            height: 3em;
            background-color: red;
            font-size: 3em;
        }
        .pold {
            font-family: '微軟黑字體','Segoe UI', Arial, 'Microsoft Jhenghei',sans-serif;
        }
    </style>
</div>
