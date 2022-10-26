<template>
    <div>
        <b-tabs content-class="mt-3">
            <b-tab title="Pesan"><p>I'm the Pesan tab</p></b-tab>
            <b-tab title="Profil" active>
                <div>
                    <b-form>
                        <b-card>
                            <b-row>
                                <b-col lg="6" md="6" sm="12">
                                    <b-form-group
                                        id="input-group-1"
                                        label="ID Toko"
                                        label-for="input-1"
                                    >
                                        <h3>180000453</h3>
                                    </b-form-group>
                                </b-col>
                                <b-col lg="6" md="6" sm="12">
                                    <b-form-group
                                        id="input-group-1"
                                        label="ID Toko"
                                        label-for="input-1"
                                    >
                                        <h3>BERKAH ANUGRAH</h3>
                                    </b-form-group>
                                </b-col>
                            </b-row>

                            <b-row>
                                <b-col lg="6" md="6" sm="12">
                                    <b-form-group
                                        id="input-group-1"
                                        label="Nama Depan"
                                        label-for="input-1"
                                    >
                                        <b-form-input
                                        id="input-1"
                                        type="email"
                                        placeholder="Nama Depan"
                                        required
                                        ></b-form-input>
                                    </b-form-group>
                                </b-col>
                                <b-col lg="6" md="6" sm="12">
                                    <b-form-group
                                        id="input-group-1"
                                        label="Nama Belakang"
                                        label-for="input-1"
                                    >
                                        <b-form-input
                                        id="input-1"
                                        type="text"
                                        placeholder="Nama Belakang"
                                        required
                                        ></b-form-input>
                                    </b-form-group>
                                </b-col>
                            </b-row>
                        </b-card>
                        <b-card>
                            <b-row>
                                <b-col lg="6" md="6" sm="12">
                                    <b-form-group
                                        id="input-group-1"
                                        label="No. Telepon / Handphone"
                                        label-for="input-1"
                                    >
                                        <b-input-group prepend="+62" class="mt-3">
                                            <b-form-input
                                            id="input-1"
                                            type="text"
                                            placeholder="No. Telepon / Handphone"
                                            required
                                            ></b-form-input>
                                            <b-input-group-append>
                                                <b-button variant="success">Simpan</b-button>
                                            </b-input-group-append>
                                        </b-input-group>
                                    </b-form-group>
                                </b-col>
                                <b-col lg="6" md="6" sm="12">
                                    <b-form-group
                                        id="input-group-1"
                                        label="Email"
                                        label-for="input-1"
                                    >
                                        <b-input-group class="mt-3">
                                            <b-form-input
                                            id="input-1"
                                            type="email"
                                            placeholder="Masukkan Email"
                                            required
                                            ></b-form-input>
                                            <b-input-group-append>
                                                <b-button variant="outline-secondary">Simpan</b-button>
                                            </b-input-group-append>
                                        </b-input-group>
                                    </b-form-group>
                                </b-col>
                            </b-row>

                            <b-row>
                                <b-col lg="6" md="6" sm="12">
                                    <b-form-group
                                        id="input-group-1"
                                        label="Informasi KTP"
                                        label-for="input-1"
                                    >
                                        <img src="~/assets/14 AksesToko Default Image KTP 969x612.png" style="width: 100%;" />
                                    </b-form-group>
                                </b-col>
                                <b-col lg="6" md="6" sm="12">
                                    <h3>Syarat dan Ketentuan</h3>
                                    <b-form-group
                                        id="input-group-1"
                                        label="Baca Syarat dan Ketentuan dibawah ini"
                                        label-for="input-1"
                                    >
                                        <b-input-group class="mt-3">
                                            <b-form-input
                                            id="input-1"
                                            type="text"
                                            placeholder="Syarat dan Ketentuan"
                                            required
                                            readonly
                                            ></b-form-input>
                                            <b-input-group-append>
                                                <b-button variant="outline-secondary">Download</b-button>
                                            </b-input-group-append>
                                        </b-input-group>
                                    </b-form-group>

                                    <b-form-group
                                        id="input-group-1"
                                        label="Baca Kebijakan Privasi dibawah ini"
                                        label-for="input-1"
                                    >
                                        <b-input-group class="mt-3">
                                            <b-form-input
                                            id="input-1"
                                            type="text"
                                            placeholder="Kebijakan Privasi"
                                            required
                                            readonly
                                            ></b-form-input>
                                            <b-input-group-append>
                                                <b-button variant="outline-secondary">Download</b-button>
                                            </b-input-group-append>
                                        </b-input-group>
                                    </b-form-group>
                                </b-col>
                            </b-row>
                        </b-card>
                    </b-form>
                </div>
            </b-tab>
            <b-tab title="Informasi Toko"><p>I'm the Informasi Toko tab</p></b-tab>
            <b-tab title="Ganti Kata Sandi"><p>I'm the Ganti Kata Sandi tab</p></b-tab>
            <b-tab title="Petunjuk Penggunaan"><p>I'm the Petunjuk Penggunaan tab</p></b-tab>
        </b-tabs>
    </div>
</template>

<script>
export default {
    name: 'Tab'
}
</script>