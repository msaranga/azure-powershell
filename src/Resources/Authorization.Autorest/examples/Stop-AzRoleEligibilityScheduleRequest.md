### Example 1: Cancel a pending role eligibility schedule request
```powershell
PS C:\> $scope = "/subscriptions/38ab2ccc-3747-4567-b36b-9478f5602f0d/"
PS C:\> $name = "47f8978c-5d8d-4fbf-b4b6-2f43eeb43ec6"
PS C:\> Stop-AzRoleEligibilitytScheduleRequest -Scope $scope -Name $name

```

You can use this operation to cancel a `roleEligibilityScheduleRequest` which has not been provisioned yet.

