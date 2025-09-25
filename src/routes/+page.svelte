<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconHeadphones from "~icons/lucide/headphones";
	import IconTemplate from "~icons/lucide/file-text";
	import IconCalendarClock from "~icons/lucide/calendar-clock";
	import IconMessageSquare from "~icons/lucide/message-square";
	import IconBarChart3 from "~icons/lucide/bar-chart-3";
	import IconUserCheck from "~icons/lucide/user-check";
</script>

<Hero
	title="Deploy AI employees that work 24/7 for your business"
	subtitle="Handle customer service, scheduling, and administrative tasks autonomously. Perfect for small business owners who need reliable support without the overhead."
	imageSrc="/generated/image-a-confident-small-business-owner-in-a-mo.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by growing businesses"
	logoUrls={[
		'https://cdn.brandfetch.io/hubspot.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/mailchimp.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/freshworks.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/intercom.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Rodriguez",
			position: "Marketing Consultant",
			company: "Rodriguez Marketing",
			quote:
				"My AI employee handles 90% of client inquiries automatically, saving me 15 hours per week.\nI've been able to take on 40% more clients without hiring additional staff, increasing revenue by $60,000 annually.",
			image: "/generated/image-a-professional-hispanic-woman-consultant.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Business Coach",
			company: "Elite Growth Coaching",
			quote:
				"The AI employee schedules all my client sessions and sends follow-ups 24/7.\nI eliminated the $50,000 annual cost of a virtual assistant while improving response times from hours to minutes.",
			image: "/generated/image-a-professional-black-man-business-coach-.webp"
		},
		{
			name: "Lisa Chen",
			position: "Freelance Designer",
			company: "Chen Creative Studio",
			quote:
				"My AI employee handles project updates and client communication seamlessly.\nI reduced administrative tasks by 70% and can now focus on creative work that generates 3x higher hourly rates.",
			image: "/generated/image-a-professional-asian-woman-freelancer-si.webp"
		}
	]}
/>

<Features
	title="AI employees built for your business"
	subtitle="Deploy intelligent workforce that understands your industry and handles operations autonomously"
	features={[
		{
			title: "24/7 customer service that never sleeps",
			description: "Handle inquiries, resolve issues, and maintain customer satisfaction around the clock without hiring additional staff.",
			icon: IconHeadphones
		},
		{
			title: "Industry-specific templates you recognize",
			description: "Start with proven workflows designed for your specific business type, eliminating the 'AI won't understand my process' concern.",
			icon: IconTemplate
		},
		{
			title: "Autonomous scheduling and admin tasks",
			description: "Manage appointments, send follow-ups, and handle routine administration so you can focus on growing your business.",
			icon: IconCalendarClock
		},
		{
			title: "Multi-channel communication management",
			description: "Respond consistently across email, chat, phone, and social media with your brand voice and business knowledge.",
			icon: IconMessageSquare
		},
		{
			title: "Real-time business intelligence",
			description: "Get actionable insights from customer interactions and operational data to make smarter decisions faster.",
			icon: IconBarChart3
		},
		{
			title: "Seamless human handoff when needed",
			description: "Maintain quality control with intelligent escalation that knows when complex issues require your personal attention.",
			icon: IconUserCheck
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
