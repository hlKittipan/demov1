<template>
  <div>
    <b-row class="justify-content-center">
      <b-col cols="12" md="6">
        <b-card
          bg-variant="dark"
          text-variant="white"
          class="mt-3 card-login"
        >
          <b-card-body>
            <b-card-text>
              <b-form>
                <b-form-group
                  id="input-group-1"
                  label="Username:"
                  label-for="input-1"
                >
                  <b-form-input id="input-1" type="text" required />
                </b-form-group>

                <b-form-group
                  id="input-group-2"
                  label="Password:"
                  label-for="input-2"
                >
                  <b-form-input id="input-2" type="password" required />
                </b-form-group>

                <b-form-group id="input-group-4">
                  <b-form-checkbox-group id="checkboxes-4">
                    <b-form-checkbox switch>
                      Remember
                    </b-form-checkbox>
                  </b-form-checkbox-group>
                </b-form-group>
                <b-row>
                  <b-col cols="12" md="12">
                    <b-button block type="submit" variant="warning">
                      Login
                    </b-button>
                  </b-col>
                </b-row>
              </b-form>
            </b-card-text>
          </b-card-body>
          <b-card-footer>
            <b-row>
              <b-col cols="6" md="6">
                <b-button block type="button" variant="outline-warning">
                  Register
                </b-button>
              </b-col>
              <b-col cols="6" md="6">
                <b-button block type="button" variant="outline-warning">
                  Contact us
                </b-button>
              </b-col>
            </b-row>
          </b-card-footer>
        </b-card>
      </b-col>
    </b-row>
  </div>
</template>
