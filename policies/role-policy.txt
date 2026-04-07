{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Principal": {
        "AWS": "arn:aws:iam::796973487906:user/vhlq0000-s"
      },
      "Action": "sts:AssumeRole",
      "Condition": {
        "StringEquals": {
          "sts:ExternalId": "EZB33299_SFCRole_5_ybTmK9YGqZPtIVK/HOu8eTXyJjI="
        }
      }
    }
  ]
}
