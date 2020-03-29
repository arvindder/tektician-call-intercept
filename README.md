## Example

    PhoneCallIntercept.onCall(function(state) {
        console.log("CHANGE STATE: " + state);

        switch (state) {
            case "RINGING":
                console.log("Phone is ringing");
                break;
            case "OFFHOOK":
                console.log("Phone is off-hook/Ongoing Call");
                break;

            case "IDLE":
                console.log("Phone is idle, call is ended");
                break;
        }
    });