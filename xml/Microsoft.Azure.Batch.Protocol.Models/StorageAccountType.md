<Type Name="StorageAccountType" FullName="Microsoft.Azure.Batch.Protocol.Models.StorageAccountType">
  <TypeSignature Language="C#" Value="public enum StorageAccountType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StorageAccountType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.StorageAccountType" />
  <TypeSignature Language="VB.NET" Value="Public Enum StorageAccountType" />
  <TypeSignature Language="F#" Value="type StorageAccountType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d32b1-101">Definiert Werte für StorageAccountType an.</span><span class="sxs-lookup"><span data-stu-id="d32b1-101">Defines values for StorageAccountType.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PremiumLRS">
      <MemberSignature Language="C#" Value="PremiumLRS" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.StorageAccountType PremiumLRS = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.StorageAccountType.PremiumLRS" />
      <MemberSignature Language="VB.NET" Value="PremiumLRS" />
      <MemberSignature Language="F#" Value="PremiumLRS = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.StorageAccountType.PremiumLRS" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="premium_lrs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StorageAccountType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d32b1-102">Die Datenträger sollten lokal redundantes Storage Premium verwenden.</span><span class="sxs-lookup"><span data-stu-id="d32b1-102">The data disk should use premium locally redundant storage.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="StandardLRS">
      <MemberSignature Language="C#" Value="StandardLRS" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.StorageAccountType StandardLRS = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.StorageAccountType.StandardLRS" />
      <MemberSignature Language="VB.NET" Value="StandardLRS" />
      <MemberSignature Language="F#" Value="StandardLRS = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.StorageAccountType.StandardLRS" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="standard_lrs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StorageAccountType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d32b1-103">Die Datenträger sollten standard lokal redundanten Speicher verwenden.</span><span class="sxs-lookup"><span data-stu-id="d32b1-103">The data disk should use standard locally redundant storage.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>