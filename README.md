# Tailwind CSS Flex Item Height Issue

This repository demonstrates an uncommon bug in Tailwind CSS related to flex item heights and provides a solution. The problem arises when flex items within a container have varying heights and fail to stretch to fill the available space. This issue is often overlooked because the default `align-items: stretch` property does not always work as expected in this scenario.

The solution involves applying the `flex-grow` utility class to the flex items.