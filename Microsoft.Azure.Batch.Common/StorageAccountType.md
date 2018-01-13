<Type Name="StorageAccountType" FullName="Microsoft.Azure.Batch.Common.StorageAccountType">
  <TypeSignature Language="C#" Value="public enum StorageAccountType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed StorageAccountType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.StorageAccountType" />
  <TypeSignature Language="VB.NET" Value="Public Enum StorageAccountType" />
  <TypeSignature Language="F#" Value="type StorageAccountType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Der speicherkontotyp zum Erstellen von Datenträgern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PremiumLrs">
      <MemberSignature Language="C#" Value="PremiumLrs" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.StorageAccountType PremiumLrs = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.StorageAccountType.PremiumLrs" />
      <MemberSignature Language="VB.NET" Value="PremiumLrs" />
      <MemberSignature Language="F#" Value="PremiumLrs = 1" Usage="Microsoft.Azure.Batch.Common.StorageAccountType.PremiumLrs" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.StorageAccountType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Die Datenträger sollten lokal redundantes Storage Premium verwenden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="StandardLrs">
      <MemberSignature Language="C#" Value="StandardLrs" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.StorageAccountType StandardLrs = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.StorageAccountType.StandardLrs" />
      <MemberSignature Language="VB.NET" Value="StandardLrs" />
      <MemberSignature Language="F#" Value="StandardLrs = 0" Usage="Microsoft.Azure.Batch.Common.StorageAccountType.StandardLrs" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.StorageAccountType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Die Datenträger sollten standard lokal redundanten Speicher verwenden.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>