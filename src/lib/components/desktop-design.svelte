<div class="container">
	<div class="info">
		<h1>Stay updated!</h1>
		<p>Join 60,000+ product managers receiving monthly updates on:</p>
		<ul>
			<li>
				<img src="assets/images/icon-list.svg" />
				<span>Product discovery and building what matters</span>
			</li>
			<li>
				<img src="assets/images/icon-list.svg" />
				<span>Measure to ensure updates are a sucess</span>
			</li>
			<li>
				<img src="assets/images/icon-list.svg" />
				<span>And much more!</span>
			</li>
		</ul>
		<label for="email">Email Address</label>
		<input type="text" name="email" id="email" placeholder="email@company.com" />
		<button>Subscribe to monthly newsletter</button>
	</div>
	<div class="graphic">
		<img src="assets/images/illustration-sign-up-desktop.svg" />
	</div>
</div>

<style lang="scss">
	.container {
		background-color: white;
		border-radius: 20px;
		box-shadow: 0 0 30px 20px rgba(0, 0, 0, 0.1);
		display: flex;
		flex-direction: row;
		gap: 2rem;
		max-width: 1000px;
		padding: 1.25rem;

		.graphic {
			display: flex;
			flex: 1;
			justify-content: flex-end;
		}

		.info {
			display: flex;
			flex-direction: column;
			justify-content: space-between;
			max-width: 500px;
			padding: 3rem;

			h1 {
				font-size: 4rem;
			}

			ul {
				list-style: none;

				li {
					font-weight: 400;
					margin: 1rem 0;

					img {
						margin-right: 1rem;
						vertical-align: middle;
					}
				}
			}

			label {
				font-weight: bold;
			}

			input {
				border: 2px solid #d6d6d6;
				border-radius: 5px;
				height: 3.5rem;
				padding: 1rem;
			}

			button {
				background: var.$dark-slate-gray;
				border: none;
				border-radius: 5px;
				box-shadow: none;
				color: white;
				cursor: pointer;
				font-weight: bold;
				height: 3.5rem;
				padding: 1rem 1rem;
				transition: transform 0.3s;

				@media (max-width: 374px) {
					margin-top: 5rem;
				}

				&:hover {
					background: linear-gradient(
						to right,
						hsla(340, 100%, 50%, 1),
						hsla(0, 100%, 50%, 1),
						hsla(10, 100%, 50%, 1)
					);
					box-shadow: 0 10px 20px 5px rgba(var.$primary-color, 0.5);
					opacity: 0.7;
					transform: scale(1.05);
				}
			}
		}
	}
</style>
