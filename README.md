# Strap-on

A sass grid system

## Usage

	<div class="grid-container">
		<div class="row">
			<div class="col-2">
				<p>Two columns</p>
			</div>
			<div class="col-10">
				<p>Ten columns</p>
				<div class="row">
					<div class="col-12">
						<p>This row is nested</p>
					</div>
				</div>	
			</div>
		</div>	
	</div>