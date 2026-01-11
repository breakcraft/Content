<div align="center">
    <h1>Lost City - July 13, 2004</h1>
</div>

> [!NOTE]
> Learn about our history and ethos on our forum: https://lostcity.rs/t/faq-what-is-lost-city/16

## Automated Workflows

This repository includes automated workflows to help maintain synchronization with the upstream repository:

### Upstream Sync
- **Schedule**: Runs daily at 00:00 UTC
- **Purpose**: Automatically syncs the fork with the upstream repository [LostCityRS/Content](https://github.com/LostCityRS/Content) (branch `245.2`)
- **Action**: When upstream has new commits, the workflow automatically merges them into this fork
- **Manual trigger**: Can be manually triggered from the Actions tab

If merge conflicts occur, the workflow will create an issue for manual resolution.

## License

Source code is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](LICENSE) file for details.

Assets within are the intellectual property of Jagex Ltd. These do not get covered by our software license.  
They were originally obtained from their official software distribution channels then extracted here, and are included for historical preservation.
