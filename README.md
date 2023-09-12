# happ-verification


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Verification 1</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="style.css">
</head>
<body>    
    <div class="container flex h-screen">
		<div class="hidden md:w-1/2 lg:block">
			<img src="assets/images/verification-1.jpg" alt="Left-Image" class="h-fit">
		</div>
		<div class="w-full flex md:items-center jusity-center md:px-24 h-full lg:w-1/2 py-4">
			<div class="details p-6 md:p-0">
				<img src="assets/images/haap-logo.svg" alt="Logo" class="mt-4 mb-8 md:hidden">
				<h1 class="text-[34.9px] font-medium md:text-[51px]">Verification</h1>
				<p class="text-[13.29px] text-sm text-[#808080]">Complete your KYC verification for compliance purposes <br class="hidden md:block">
					in just 4 simple steps
				</p>

				<!-- Progress Bar -->
				<div class="mx-auto my-3">	
					<div class="flex py-2 w-full">
						<div>
							<div class="w-10 h-10 bg-[#3284A0] rounded-full text-lg text-white flex items-center">
								<span class="text-white text-center font-medium w-full">1</i></span>
							</div>
						</div>


						<div class="w-1/6 align-center items-center align-middle content-center flex">
							<div class="w-full rounded items-center align-middle align-center flex-1">
								<div class="border border-[#808080]"></div>
							</div>
						</div>
					
						
						<div>
							<div class="w-10 h-10 border border-[#808080] rounded-full text-lg text-white flex items-center">
								<span class="text-[#808080] text-center font-medium w-full">2</i></span>
							</div>
						</div>


						<div class="w-1/6 align-center items-center align-middle content-center flex">
							<div class="w-full rounded items-center align-middle align-center flex-1">
								<hr class="border border-[#808080]">
							</div>
						</div>
					
						<div>
							<div class="w-10 h-10 border border-[#808080] rounded-full text-lg text-white flex items-center">
								<span class="text-[#808080] text-center font-medium w-full">3</i></span>
							</div>
						</div>


						<div class="w-1/6 align-center items-center align-middle content-center flex">
							<div class="w-full rounded items-center align-middle align-center flex-1">
								<hr class="border border-[#808080]">
							</div>
						</div>


						<div>
							<div class="w-10 h-10 border border-[#808080] rounded-full text-lg text-white flex items-center">
								<span class="text-[#808080] text-center font-medium w-full">4</i></span>
							</div>
						</div>	
					</div>
				</div>

				<!-- Form -->
				<div>
					<h1 class="text-[24px] font-medium md:text-[33px]">Email Verification</h1>
					<p class="text-[13.29px] text-sm text-[#808080]">
						Enter the code sent to your email address
                        to continue with verification
					</p>

                    <div class="input-group flex space-x-4 my-4">
                        <input class="border-2 h-14 w-14 text-center font-semibold border-[#0A1A1F] text-xl form-control rounded-lg" type="text" id="first" maxlength="1" /> 
                        <input class="border-2 h-14 w-14 text-center font-semibold border-[#0A1A1F] text-xl form-control rounded-lg" type="text" id="second" maxlength="1" /> 
                        <input class="border-2 h-14 w-14 text-center font-semibold border-[#0A1A1F] text-xl form-control rounded-lg" type="text" id="third" maxlength="1" /> 
                        <input class="border-2 h-14 w-14 text-center font-semibold border-[#0A1A1F] text-xl form-control rounded-lg" type="text" id="fourth" maxlength="1" />
                    </div>

					<button class="mt-5 w-full bg-[#3284A0] rounded-lg p-3 text-base text-white">Submit</button>
                    <p class="text-sm lg:text-base text-[#808080] mt-3">
						Didn’t receive an email? 
                        <span class="font-semibold text-[#3284A0]">
                            Resend 03
                        </span>
					</p>
				</div>
			</div>
		</div>
	</div>
</body>
</html>