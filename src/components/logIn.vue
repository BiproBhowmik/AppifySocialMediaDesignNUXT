<template>
    <div>
        <div class="_2menu">
            <div class="_2menu_con">
                <div class="row align-items-center">
                    <div class="col">
                        <router-link to="/">
                            <h3 class="_menu_logo_text">
                                <span class="_menu_logo_symbol">C</span>
                                <span class="_menu_logo_text_main">CONNECTIVER</span>
                            </h3>
                        </router-link>
                    </div>

                    <div class="col-auto">
                        <router-link to="/signUp">
                            <button class="_log_btn _2menu_long" type="button">Sign Up</button>
                        </router-link>
                    </div>
                </div>
            </div>
        </div>

        <!-- Banner -->
        <div class="_4banner">
            <div class="_4banner_main">
                <h1 class="_4banner_title">Connectiver</h1>
                <p class="_4banner_text">Creating a conscious and safe community where human<br/> connection and new ideas can thrive</p>
            </div>
        </div>
        <!-- Banner -->

        <!-- Form -->
        <div class="_log_form_main">
            <h2 class="_log_form_title">Login</h2>

            <div class="_log_form">
                <div class="_log_input_group">
                    <input class="_log_input" placeholder="Email" type="text">
                </div>
                <div class="_log_input_group">
                    <input class="_log_input" placeholder="Password" type="password">
                </div>
                <div class="_log_button">
                    <button class="_log_btn _btn_long">Login</button>
                </div>

                <p class="_log_forget"><router-link to="/forgetPassword">Forgot password?</router-link></p>
            </div>
        </div>
        <!-- Form -->
    </div>
</template>