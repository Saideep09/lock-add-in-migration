****Below is the CLI command that can be used to list the branch protection rules for a branch:****


**EX:1**
**C:\Users\saide>gh api -X GET repos/saideep11111/source2/branches/main/protection**
{
  "url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection",
  "required_status_checks": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/required_status_checks",
    "strict": false,
    "contexts": [],
    "contexts_url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/required_status_checks/contexts",
    "checks": []
  },
  "restrictions": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/restrictions",
    "users_url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/restrictions/users",
    "teams_url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/restrictions/teams",
    "apps_url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/restrictions/apps",
    "users": [],
    "teams": [],
    "apps": []
  },
  "required_pull_request_reviews": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/required_pull_request_reviews",
    "dismiss_stale_reviews": false,
    "require_code_owner_reviews": false,
    "require_last_push_approval": false,
    "required_approving_review_count": 1
  },
  "required_signatures": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/required_signatures",
    "enabled": true
  },
  "enforce_admins": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection/enforce_admins",
    "enabled": false
  },
  "required_linear_history": {
    "enabled": true
  },
  "allow_force_pushes": {
    "enabled": false
  },
  "allow_deletions": {
    "enabled": false
  },
  "block_creations": {
    "enabled": true
  },
  "required_conversation_resolution": {
    "enabled": true
  },
  "lock_branch": {
    "enabled": false
  },
  "allow_fork_syncing": {
    "enabled": false
  }
}

**EX:2**

**C:\Users\saide>gh api -X GET repos/saideep11111/source2/branches/branch1/protection**

{
  "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch1/protection",
  "required_pull_request_reviews": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch1/protection/required_pull_request_reviews",
    "dismiss_stale_reviews": false,
    "require_code_owner_reviews": false,
    "require_last_push_approval": false,
    "required_approving_review_count": 2
  },
  "required_signatures": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch1/protection/required_signatures",
    "enabled": true
  },
  "enforce_admins": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch1/protection/enforce_admins",
    "enabled": true
  },
  "required_linear_history": {
    "enabled": false
  },
  "allow_force_pushes": {
    "enabled": false
  },
  "allow_deletions": {
    "enabled": false
  },
  "block_creations": {
    "enabled": false
  },
  "required_conversation_resolution": {
    "enabled": false
  },
  "lock_branch": {
    "enabled": false
  },
  "allow_fork_syncing": {
    "enabled": false
  }
}

**ex:3**

***C:\Users\saide>gh api -X GET repos/saideep11111/source2/branches/branch2/protection***

{
  "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch2/protection",
  "required_status_checks": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch2/protection/required_status_checks",
    "strict": false,
    "contexts": [],
    "contexts_url": "https://api.github.com/repos/Saideep11111/source2/branches/branch2/protection/required_status_checks/contexts",
    "checks": []
  },
  "required_pull_request_reviews": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch2/protection/required_pull_request_reviews",
    "dismiss_stale_reviews": false,
    "require_code_owner_reviews": true,
    "require_last_push_approval": false,
    "required_approving_review_count": 1
  },
  "required_signatures": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch2/protection/required_signatures",
    "enabled": false
  },
  "enforce_admins": {
    "url": "https://api.github.com/repos/Saideep11111/source2/branches/branch2/protection/enforce_admins",
    "enabled": true
  },
  "required_linear_history": {
    "enabled": false
  },
  "allow_force_pushes": {
    "enabled": false
  },
  "allow_deletions": {
    "enabled": false
  },
  "block_creations": {
    "enabled": false
  },
  "required_conversation_resolution": {
    "enabled": false
  },
  "lock_branch": {
    "enabled": false
  },
  "allow_fork_syncing": {
    "enabled": false
  }
}



****Here is the CLI for branches****

**C:\Users\saide>gh api -X GET repos/Saideep11111/source2/branches**

[
  {
    "name": "branch1",
    "commit": {
      "sha": "46d100d04eb640834ee188e0a5938b3d3e773730",
      "url": "https://api.github.com/repos/Saideep11111/source2/commits/46d100d04eb640834ee188e0a5938b3d3e773730"
    },
    "protected": true,
    "protection": {
      "enabled": true,
      "required_status_checks": {
        "enforcement_level": "off",
        "contexts": [],
        "checks": []
      }
    },
    "protection_url": "https://api.github.com/repos/Saideep11111/source2/branches/branch1/protection"
  },
  {
    "name": "branch2",
    "commit": {
      "sha": "46d100d04eb640834ee188e0a5938b3d3e773730",
      "url": "https://api.github.com/repos/Saideep11111/source2/commits/46d100d04eb640834ee188e0a5938b3d3e773730"
    },
    "protected": true,
    "protection": {
      "enabled": true,
      "required_status_checks": {
        "enforcement_level": "everyone",
        "contexts": [],
        "checks": []
      }
    },
    "protection_url": "https://api.github.com/repos/Saideep11111/source2/branches/branch2/protection"
  },
  {
    "name": "branch4",
    "commit": {
      "sha": "46d100d04eb640834ee188e0a5938b3d3e773730",
      "url": "https://api.github.com/repos/Saideep11111/source2/commits/46d100d04eb640834ee188e0a5938b3d3e773730"
    },
    "protected": false,
    "protection": {
      "enabled": true,
      "required_status_checks": {
        "enforcement_level": "off",
        "contexts": [],
        "checks": []
      }
    },
    "protection_url": "https://api.github.com/repos/Saideep11111/source2/branches/branch4/protection"
  },
  {
    "name": "branch5",
    "commit": {
      "sha": "46d100d04eb640834ee188e0a5938b3d3e773730",
      "url": "https://api.github.com/repos/Saideep11111/source2/commits/46d100d04eb640834ee188e0a5938b3d3e773730"
    },
    "protected": false,
    "protection": {
      "enabled": true,
      "required_status_checks": {
        "enforcement_level": "off",
        "contexts": [],
        "checks": []
      }
    },
    "protection_url": "https://api.github.com/repos/Saideep11111/source2/branches/branch5/protection"
  },
  {
    "name": "main",
    "commit": {
      "sha": "46d100d04eb640834ee188e0a5938b3d3e773730",
      "url": "https://api.github.com/repos/Saideep11111/source2/commits/46d100d04eb640834ee188e0a5938b3d3e773730"
    },
    "protected": true,
    "protection": {
      "enabled": true,
      "required_status_checks": {
        "enforcement_level": "non_admins",
        "contexts": [],
        "checks": []
      }
    },
    "protection_url": "https://api.github.com/repos/Saideep11111/source2/branches/main/protection"
  },
  {
    "name": "other",
    "commit": {
      "sha": "46d100d04eb640834ee188e0a5938b3d3e773730",
      "url": "https://api.github.com/repos/Saideep11111/source2/commits/46d100d04eb640834ee188e0a5938b3d3e773730"
    },
    "protected": false,
    "protection": {
      "enabled": false,
      "required_status_checks": {
        "enforcement_level": "off",
        "contexts": [],
        "checks": []
      }
    },
    "protection_url": "https://api.github.com/repos/Saideep11111/source2/branches/other/protection"
  }
]
