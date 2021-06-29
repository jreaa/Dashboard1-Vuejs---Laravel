<template>
    <div>

		<!--end::Header Mobile-->
		<div class="d-flex flex-column flex-root">
			<!--begin::Page-->
			<div class="d-flex flex-row flex-column-fluid page">
				<Aside></Aside>
				<!--begin::Wrapper-->
				<div class="d-flex flex-column flex-row-fluid wrapper" id="kt_wrapper">
					<Header></Header>
					<!--begin::Content-->
					<div class="content d-flex flex-column flex-column-fluid" id="kt_content">

						<!--begin::Entry-->
						<div class="d-flex flex-column-fluid">
                             <main class="container" style="padding-bottom: 50px;">
                                
                            </main>
						</div>
						<!--end::Entry-->
					</div>
					<!--end::Content-->
                    <Footer></Footer>
				</div>
				<!--end::Wrapper-->
			</div>
			<!--end::Page-->
		</div>
		<!--end::Main-->
    </div>
</template>  

<script>
import Aside from '../Layouts/Aside.vue'
import Header from '../Layouts/Header.vue'
import Footer from '../Layouts/Footer.vue'
export default {
    components: {
        Aside,
        Header,
        Footer
    }
}
</script>