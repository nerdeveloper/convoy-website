<template>
	<div>
		<section class="bg-[linear-gradient(248deg,#32587D_14%,#0f2a44f5_88%)] pt-200px pb-100px desktop:pt-250px desktop:pb-150px">
			<div class="max-w-[1280px] m-auto flex footer:flex-wrap justify-between items-center px-20px">
				<div>
					<h1 class="text-white-100 desktop:text-[56px] desktop:leading-[80px] max-w-[580px] font-bold footer:text-center">High-performance Webhooks Gateway</h1>
					<p class="text-white-100 max-w-[580px] mx-auto text-18 mobile:text-14 mt-16px footer:text-center">
						Manage billions of both incoming and outgoing webhook events while staying fully compliant by being in total control of your data on-premise.
					</p>
					<div class="flex footer:justify-center mt-40px">
						<a
							href="#requestAccess"
							class="py-12px desktop:py-16px px-38px desktop:px-42px text-14 font-medium rounded-8px bg-primary-100 text-white-100 text-center mr-24px xs:mr-0 xs:mb-20px xs:w-full"
						>
							Get Started
						</a>
					</div>
				</div>
				<div>
					<img src="~/assets/images/enterprise.png" class="max-h-[436px]" alt="enterprise image" />
				</div>
			</div>
		</section>

		<section class="py-120px desktop:py-160px">
			<div class="max-w-[1350px] m-auto px-20px">
				<h1 class="text-[48px] leading-[56px] font-bold text-center">Do more with Convoy Enterprise.</h1>

				<div class="flex justify-between flex-wrap gap-6 mt-80px desktop:mt-120px">
					<div class="desktop:max-w-[340px]">
						<img src="~/assets/images/everything-you-need.png" class="mb-16px rounded-8px shadow-[0px_22px_24px_rgba(65,111,244,0.2)]" alt="everything-you-need" />
						<p class="text-14 desktop:text-20">Granular role based access control, ensuring authorized access to infrastructure for large organizations.</p>
					</div>
					<div class="desktop:max-w-[400px]">
						<img src="~/assets/images/excellent-rate-limiting.png" class="mb-16px rounded-8px shadow-[0px_22px_24px_rgba(43,214,123,0.2)]" alt="excellent-rate-limiting" />
						<p class="text-14 desktop:text-20">Efficiently create separate environments for development, staging, and production, enabling faster iteration, and improved software delivery.</p>
					</div>
					<div class="desktop:max-w-[340px]">
						<img src="~/assets/images/transparent-pricing.png" class="mb-16px rounded-8px shadow-[0px_22px_24px_rgba(247,227,109,0.2)]" alt="transparent-pricing" />
						<p class="text-14 desktop:text-20">Detailed Audit Logs so your team can tracks all user actions and event calls for compliance and security purposes.</p>
					</div>
				</div>
			</div>
		</section>

		<section class="px-20px">
			<div class="rounded-[20px] desktop:rounded-[70px] mx-auto bg-[linear-gradient(248deg,#32587D_14%,#0f2a44f5_88%)] max-w-[1350px]">
				<div class="w-full md:bg-[url(~/assets/images/Settings.png)] bg-no-repeat bg-right desktop:bg-contain rounded-[70px] min-h-[200px] py-30px desktop:py-56px px-20px desktop:px-70px">
					<p class="font-bold text-white-100 text-24 desktop:text-32 max-w-[690px]">
						Engineering teams that value efficiency use
						<span class="text-primary-300">Convoy</span>
						to manage webhook events.
					</p>

					<ul class="flex items-center list-none mt-38px">
						<li class="mr-12px">
							<a target="_blank" rel="noopener noreferrer" href="https://www.drivehailify.com/">
								<img src="~/assets/images/hailify-logo.svg" alt="hailify logo" />
							</a>
						</li>
						<li class="mr-12px">
							<a target="_blank" rel="noopener noreferrer" href="https://www.piggyvest.com/">
								<img src="~/assets/images/piggyvest.svg" alt="piggyvest logo" />
							</a>
						</li>
						<li class="mr-12px">
							<a target="_blank" rel="noopener noreferrer" href="https://www.catlog.shop/">
								<img src="~/assets/images/Catlog.svg" alt="catlog logo" />
							</a>
						</li>
						<li class="mr-12px">
							<a target="_blank" rel="noopener noreferrer" href="https://www.payourse.com/">
								<img src="~/assets/images/payourse.svg" class="mt-4px" alt="payourse logo" />
							</a>
						</li>
						<li class="mr-12px hidden desktop:block">
							<a target="_blank" rel="noopener noreferrer" href="https://buycoins.africa/">
								<img src="~/assets/images/buycoins.svg" alt="buycoins logo" />
							</a>
						</li>
						<li class="mr-12px hidden desktop:block">
							<a target="_blank" rel="noopener noreferrer" href="https://www.getwallets.co/">
								<img src="~/assets/images/getwallets.svg" alt="getwallets logo" />
							</a>
						</li>
						<li class="mr-12px hidden desktop:block">
							<a target="_blank" rel="noopener noreferrer" href="https://www.dojah.io/">
								<img src="~/assets/images/dojah.svg" alt="dojah logo" />
							</a>
						</li>
						<li class="mr-12px hidden desktop:block">
							<a target="_blank" rel="noopener noreferrer" href="https://termii.com/">
								<img src="~/assets/images/termii.svg" alt="termii logo" />
							</a>
						</li>
					</ul>
				</div>
			</div>
		</section>

		<section class="bg-white-100 py-100px px-20px" id="requestAccess">
			<div class="max-w-[1350px] m-auto flex flex-wrap items-center justify-between">
				<div>
					<h1 class="font-bold text-32 max-w-[480px] mb-60px">Enterprise-ready Webhooks Gateway</h1>
					<div class="flex items-start mb-48px" v-for="feature in enterpriseFeatures" :key="feature">
						<img src="~/assets/images/svg/light-lightening.svg" alt="lightening" class="mr-18px" />
						<p class="text-18 font-light mobile:text-14 md:max-w-[542px]">{{ feature }}</p>
					</div>
				</div>
				<div class="max-w-[566px]">
					<EnterpriseWaitlist></EnterpriseWaitlist>
				</div>
			</div>
		</section>

		<section class="px-20px pb-100px desktop:pb-130px">
			<div class="mt-100px desktop:mt-130px max-w-[1000px] w-full m-auto bg-[url(~/assets/images/cta.png)] bg-no-repeat bg-cover bg-top bg-blend-normal bg-[#422F41] rounded-16px py-56px px-20px">
				<h1 class="text-32 desktop:text-[40px] text-white-100 font-bold tracking-[0.02em] text-center mb-20px max-w-[562px] m-auto">Start sending and receiving webhooks now, risk free</h1>
				<p class="text-center text-14 desktop:text-18 text-white-100 max-w-[806px] m-auto">
					Convoy provides you with fast, secure and reliable webhooks infrastructure so you can focus on building the actual tech. Save yourself some engineering time and get started today.
				</p>
				<a href="#requestAccess" class="bg-primary-100 m-auto text-white-100 whitespace-nowrap text-12 desktop:text-18 font-semibold flex items-center py-12px px-24px rounded-8px mt-40px w-fit">
					Request Access
					<img src="~/assets/images/arrow-right-icon.svg" class="ml-12px" alt="arrow right" />
				</a>
			</div>
		</section>
	</div>
</template>

<script>
export default {
	layout: 'home',
	data() {
		return {
			enterpriseFeatures: [
				'Have a dedicated Customer Success team assigned to your organisational needs.',
				'With on-prem, you can create a private instance of your webhooks infrastructure and pass all security requirements pertaining to your scale.',
				'Own your data and stay compliant by deploying in regions of your choosing.',
				'Handle billions of webhook events reliably.'
			]
		};
	}
};
</script>
