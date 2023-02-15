<template>
    <section class="main-features flex">
        <Transition name="slide-left" appear>
            <div class="flex column main-feature">
                <img src="../assets/svgs/icon-access-anywhere.svg" alt="">
                <h3>Access your files, anywhere</h3>
                <p>The ability to use a smartphone, tablet,
                    or computer to access your account means your files follow you everywhere.</p>
            </div>
        </Transition>
        <Transition name="slide-left" appear>
            <div class="flex column main-feature">
                <img src="../assets/svgs/icon-security.svg" alt="">
                <h3>Access your files, anywhere</h3>
                <p>2-factor authentication and user-controlled
                    encryption are just a couple of the security features we allow to help secure your files.</p>
            </div>
        </Transition>
        <Transition name="slide-right" appear>
            <div class="flex column main-feature">
                <img src="../assets/svgs/icon-collaboration.svg" alt="">
                <h3>Access your files, anywhere</h3>
                <p>Securely share files and folders with friends,
                    family and colleagues for live collaboration. No email attachments required.</p>
            </div>
        </Transition>
        <Transition name="slide-right" appear>
            <div class="flex column main-feature">
                <img src="../assets/svgs/icon-any-file.svg" alt="">
                <h3>Access your files, anywhere</h3>
                <p>Whether you're sharing holidays photos or work documents,
                    Fylo has you covered allowing for all file types to be securely stored and shared.</p>
            </div>
        </Transition>
    </section>
</template>