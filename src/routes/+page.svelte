<script>
    import Card1 from '$lib/components/Card1.svelte';
    import Card2 from '$lib/components/Card2.svelte';
    import Card3 from '$lib/components/Card3.svelte';
    import Card4 from '$lib/components/Card4.svelte';
    import dash from '$lib/images/valid_dash.png';
    import employees from '$lib/images/valid_employees.png'
    import stats from '$lib/images/valid_stats.png'
</script>


<div class="mb-8 text-white text-center p-6 m-6 px-[10rem] mt-[5rem]">
<h1 class="text-5xl font-bold">Don't Just Secure It!</h1>
<h1 class = "text-9xl font-bold">Validify It!</h1>
<p class="p-6 px-10 m-6 text-3xl">Secure Your Project Data and Metrics with Blockchain and AI</p>

<a class="bg-black py-4 px-7 rounded-xl hover:bg-white hover:text-black ease-in-out duration-300 font-bold" href="/about">About Us</a>

</div>

<div class="p-8">
    <img src={dash} alt="" class="w-[80rem] m-auto border-[#826cff] border-[1rem] rounded-[2rem] shadow-lg">

</div>

<div class="bg-white p-8">
    <div class="flex items-center justify-between p-8 gap-5">
        <div class="p-8">
            <h1 class="text-5xl font-bold">Business Benefits</h1>
            <p class="mt-4">Verify and Validate the Quality of your Projects and Project Contributors</p>
        </div>
    </div>
    <div class="grid-cols-2 grid gap-4 p-8 px-[5rem]">
        <Card1/>
        <Card2/>
        <Card3/>
        <Card4/>
    </div>
</div>

<div class="p-8 bg-white">
    <div class="flex items-center p-8 justify-between gap-4">
        <div>
            <img src={stats} alt="" class="w-[45rem] hover:w-[48rem] ease-in-out duration-300">
        </div>
        <div class="p-6">
            <h1 class="text-5xl font-bold">Validify Your Projects!</h1>
            <p class="mt-4">Advertise Your Quality with a Validify NFT Badge for Your Project, Company, and Assets that Links to your Public Blockchain Secured Reports and Data to Prove your Project Quality and Security.</p>
        </div>
    </div>
</div>

<div class="p-8 bg-purple">
    <div class="flex items-center p-8 justify-between gap-4">
        <div>
            <img src={stats} alt="" class="w-[45rem] hover:w-[48rem] ease-in-out duration-300">
        </div>
        <div class="p-6">
            <h1 class="text-5xl font-bold">Validify Your Audits!</h1>
            <p class="mt-4">Both Public and Private Reports of Project Quality and Standards Can Be Validified With Our Blockchain. This Automated Collection, Management, and Controlled Access to Detailed Reprots Can Save Hundreds of Thousands of Dollars Per Year in Time and Resources Dedicated to Regular Audits and Reporting Processes.</p>
        </div>
    </div>
</div>

<div class="p-8 bg-white">
    <div class="flex items-center p-8 justify-between gap-4">
        <div>
            <img src={employees} alt="" class="w-[45rem] hover:w-[48rem] ease-in-out duration-300">
        </div>
        <div class="p-6">
            <h1 class="text-5xl font-bold">Validify Your Employees!</h1>
            <p class="mt-4">Every Project Contributor Receives and NFT Badge as Proof of Their Project Contribution and Related Metrics. This Data Can be Validiated Securely Across Companies Without Risking Confidential or Secure Data. Validate Your Employees and Contractors Are Top Quality and Have Proven Experience. </p>
        </div>
    </div>
</div>

