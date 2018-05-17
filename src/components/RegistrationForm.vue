<template>
    <div class="platform-reg-form">
        <form action="/">
            <div class="platform">
                <div class="platform-group">
                    <label for="reg_name" class="platform-label">Name</label>
                    <input type="text" name="reg_name" placeholder="John Doe" class="platform-input">
                </div>
            </div>
            <div class="platform">
                <div class="platform-group">
                    <label for="reg_gender" class="platform-label">Gender</label>

                    <div class="platform-radio-group">
                        <div class="cc-selector">
                            <div class="peachselector">
                                <div class="eachselector">
                                    <input id="platform-male" type="radio" name="gender" value="male" />
                                    <label class="drinkcard-cc male" for="platform-male"></label>
                                </div>
                                <span>Male</span>
                            </div>

                            <div class="peachselector">
                                <div class="eachselector">
                                    <input id="platform-female" type="radio" name="gender" value="female" />
                                    <label class="drinkcard-cc female" for="platform-female"></label>
                                </div>
                                <span>Female</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="platform">
                <div class="platform-group">
                    <label for="reg_dob" class="platform-label">Date of Birth</label>
                    <input type="email" name="reg_dob" placeholder="01/02/1983" class="platform-input">
                </div>
            </div>
            <div class="platform">
                <div class="platform-group">
                    <label for="reg_email" class="platform-label">Email</label>
                    <input type="email" name="reg_email" placeholder="johndoe@example.com" class="platform-input">
                </div>
            </div>
            <div class="platform">
                <div class="platform-group">
                    <label for="reg_mobile" class="platform-label">Mobile</label>
                    <input type="number" name="reg_mobile" placeholder="0747564735" class="platform-input">
                </div>
            </div>
            <div class="platform">
                <div class="platform-group">
                    <label for="reg_cId" class="platform-label">Customer ID</label>
                    <input type="text" name="reg_cId" placeholder="576802-ERD0348-45" class="platform-input">
                </div>
            </div>
            <div class="platform">
                <div class="platform-group">
                    <label for="reg_gender" class="platform-label">Membership</label>

                    <div class="platform-radio-group">
                        <div class="cc-selector">
                            <div class="peachselector">
                                <div class="eachselector">
                                    <input id="platform-classic" type="radio" name="group" value="classic" />
                                    <label class="drinkcard-cc group" for="platform-classic"></label>
                                </div>
                                <span>Classic</span>
                            </div>

                            <div class="peachselector">
                                <div class="eachselector">
                                    <input id="platform-silver" type="radio" name="group" value="silver" />
                                    <label class="drinkcard-cc group" for="platform-silver"></label>
                                </div>
                                <span>Silver</span>
                            </div>

                            <div class="peachselector">
                                <div class="eachselector">
                                    <input id="platform-gold" type="radio" name="group" value="gold" />
                                    <label class="drinkcard-cc group" for="platform-gold"></label>
                                </div>
                                <span>Gold</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="platform">
                <div class="platform-group">
                    <div class="button-group">
                        <button type="reset" class="cancel-button">Cancel</button>
                        <button type="submit" class="save-button">Save</button>
                    </div>
                </div>
            </div>
        </form>
    </div>
</template>

<script>
export default {
    name: 'reg-form'
}
</script>
