<template>
    <div class="pages">
        <h1 class="text-center">Products</h1>
        <div class="row text-center">
        <div class="col-12 col-md-6 satu q-pa-md">
         <q-card class="my-card">
            <img src="statics/guitar.png">
            <q-card-section>
                <div class="text-h5">Gibson Black Guardian</div>
                <div class="text-h6">$170</div>
                <div class="text-subtitle1">Category : Guitar</div>
            </q-card-section>
            <q-card-section class="q-pt-none">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad consectetur placeat dignissimos enim! Iste, sapiente veritatis tempora minima consectetur delectus </p>
                 <q-separator />
                 <q-card-actions> <q-btn color="secondary" label="Review Product" /></q-card-actions>
            </q-card-section>
        </q-card>
      </div>
      <div class="col-12 col-md-6 satu q-pa-md">
         <q-card class="my-card">
            <img src="statics/piano.jpg">
            <q-card-section>
                <div class="text-h5">Scarlet Phantom</div>
                <div class="text-h6">$350</div>
                <div class="text-subtitle1">Category : Piano</div>
            </q-card-section>
            <q-card-section class="q-pt-none">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad consectetur placeat dignissimos enim! Iste, sapiente veritatis tempora minima consectetur delectus </p>
                 <q-separator />
                 <q-card-actions> <q-btn color="secondary" label="Review Product" /></q-card-actions>
            </q-card-section>
        </q-card>
      </div>
      <div class="col-12 col-md-6 satu q-pa-md">
         <q-card class="my-card">
            <img src="statics/drum.jpg">
            <q-card-section>
                <div class="text-h5">DW silverLight</div>
                <div class="text-h6">$270</div>
                <div class="text-subtitle1">Category : Drum</div>
            </q-card-section>
            <q-card-section class="q-pt-none">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad consectetur placeat dignissimos enim! Iste, sapiente veritatis tempora minima consectetur delectus </p>
                 <q-separator />
                 <q-card-actions>  <q-btn outline color="primary" label="Review Product" class="text-center"/></q-card-actions>
            </q-card-section>
        </q-card>
      </div>
      <div class="col-12 col-md-6 satu q-pa-md">
         <q-card class="my-card">
            <img src="statics/biola.jpg">
            <q-card-section>
                <div class="text-h5">Biola sandwood</div>
                <div class="text-h6">$40</div>
                <div class="text-subtitle1">Category : Biola</div>
            </q-card-section>
            <q-card-section class="q-pt-none">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad consectetur placeat dignissimos enim! Iste, sapiente veritatis tempora minima consectetur delectus </p>
                 <q-separator />
                 <q-card-actions>  <q-btn outline color="primary" label="Review Product" class="text-center"/></q-card-actions>
            </q-card-section>
        </q-card>
      </div>
    </div>
    </div>
</template>

<script>

</script>

<style>
.satu {
    /* border:1px solid silver; */
}

p {
    color: gray;
}

.my-card {
    width: 80%;
    margin: 2px auto;
}

q-btn {
    border: 4px solid red;
}

.text-h5 {
    font-weight: bold;
}

h1{
    text-shadow: gray 2px 2px 4px;
}
.pages {
    padding: 30px;
}
</style>
