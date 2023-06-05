<script lang="ts">
	let email = 'ash@loremcompany.com';
</script>

<div class="container">
	<svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" viewBox="0 0 64 64">
		<defs>
			<linearGradient id="a" x1="100%" x2="0%" y1="0%" y2="100%">
				<stop offset="0%" stop-color="#FF6A3A" /><stop offset="100%" stop-color="#FF527B" />
			</linearGradient>
		</defs>
		<g fill="none"
			><circle cx="32" cy="32" r="32" fill="url(#a)" /><path
				stroke="#FFF"
				stroke-width="4"
				d="m18.286 34.686 8.334 7.98 19.094-18.285"
			/>
		</g>
	</svg>
	<h1>Thank you for subscribing!</h1>
	<p>
		A confirmation email has been sent to <a href="/">{email}</a>. Please open it and click the
		button inside to confirm your subscription.
	</p>
	<button> Dismiss message </button>
</div>

<style lang="scss">
	.container {
		display: flex;
		flex-direction: column;
		background-color: white;
		max-width: 400px;
		border-radius: 20px;
		padding: 3rem;
		gap: 1rem;
		box-shadow: 0 0 30px 20px rgba(0, 0, 0, 0.1);

		svg {
			width: 50px;
			height: 50px;
		}

		p {
			margin-bottom: 1rem;
		}

		button {
			background-color: var.$primary-color;
			color: white;
			font-weight: 400;
			padding: 0.75rem 1rem;
			border: none;
			border-radius: 5px;
			box-shadow: none;
		}
	}
</style>
