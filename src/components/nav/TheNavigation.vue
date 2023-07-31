<template>
    <section>
        <b-img left src="https://dementia.org.sg/wp-content/uploads/2021/03/DSG-Logo-Full-Colour.png" class="m-4"
            style="width: 13rem;" alt="Left image"></b-img>

        <b-container>
            <header align="center" class="my-5">
                <h1 class="p-2">Admin Homepage</h1>
            </header>
            <b-row>
                <b-col class="py-4 px-4 mx-5 my-2" style="border-radius: 10px; background-color: #50276D; padding: 20px;" align-v="stretch">
                    <p
                        style="font-weight: 400; color: white; font-size: x-large; display: flex; justify-content: center; align-items: center;">
                        Client Registration</p>
                    <b-row style="margin-top: 3.5rem;">
                        <b-button class="my-1" variant="light">Upcoming Assessment Appointment</b-button>
                        <b-button class="my-1" variant="light">List of Client (Active)</b-button>
                    </b-row>
                </b-col>
                <b-col class="py-4 px-4 mx-5 my-2" style="border-radius: 10px; background-color: #50276D; padding: 20px;" align-v="stretch">
                    <p
                        style="font-weight: 400; color: white; font-size: x-large; display: flex; justify-content: center; align-items: center;">
                        Session Info</p>
                    <b-row style="margin-top: 3.5rem;">
                        <b-button class="my-1" variant="light">Master Schedule</b-button>
                        <b-button class="my-1" variant="light">Weekly Schedule</b-button>
                    </b-row>
                </b-col>
                <b-col class="py-4 px-4 mx-5 my-2" style="border-radius: 10px; background-color: #50276D; padding: 20px;" align-v="stretch">
                    <p
                        style="font-weight: 400; color: white; font-size: x-large; display: flex; justify-content: center; align-items: center;">
                        Appointments</p>
                    <b-row style="margin-top: 3.5rem;">
                        <b-button class="my-1" variant="light">List of Appointments</b-button>
                    </b-row>
                </b-col>
                
            </b-row>
        </b-container>
        <!-- <ul>
            <div>
                <p>Client Registration</p>
                <ul>
                    <li>
                        <router-link to="/upcoming">Upcoming Assessment Appointment</router-link>
                    </li>
                    <li>
                        <router-link to="/client">List of Client (Active)</router-link>
                    </li>
                </ul>
            </div>
            <div>
                <p>Session Info</p>
                <ul>
                    <li>
                        <router-link to="/master">Master Schedule</router-link>
                    </li>
                    <li>
                        <router-link to="/weekly">Weekly Schedule</router-link>
                    </li>
                </ul>
            </div>
            <div>
                <p>Appointments</p>
                <ul>
                    <li>
                        <router-link to="/appointment">List of Appointment</router-link>
                    </li>
                </ul>
            </div>
        </ul> -->
    </section>
</template>
  