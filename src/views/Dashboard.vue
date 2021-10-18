<template>
  <div>
    <h1>Dashboard</h1>

    <Notification />

    <Form />

    <Table />
  </div>
</template>

<script>
import Notification from "../components/Notification.vue";
import Form from "../components/Form.vue";
import Table from "../components/Table.vue";

export default {
  name: "Dashboard",
  components: { Notification, Form, Table },
};
</script>
