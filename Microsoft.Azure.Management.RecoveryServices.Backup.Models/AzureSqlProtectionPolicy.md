<Type Name="AzureSqlProtectionPolicy" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy">
  <TypeSignature Language="C#" Value="public class AzureSqlProtectionPolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlProtectionPolicy extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlProtectionPolicy&#xA;Inherits ProtectionPolicy" />
  <TypeSignature Language="F#" Value="type AzureSqlProtectionPolicy = class&#xA;    inherit ProtectionPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("AzureSql")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="15bd6-101">Azure SQL-spezifische Sicherung Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="15bd6-101">Azure SQL workload-specific backup policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlProtectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15bd6-102">Initialisiert eine neue Instanz der AzureSqlProtectionPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="15bd6-102">Initializes a new instance of the AzureSqlProtectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlProtectionPolicy (Nullable&lt;int&gt; protectedItemsCount = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy retentionPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; protectedItemsCount, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy retentionPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy.#ctor(System.Nullable{System.Int32},Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy : Nullable&lt;int&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy (protectedItemsCount, retentionPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protectedItemsCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy" />
      </Parameters>
      <Docs>
        <param name="protectedItemsCount"><span data-ttu-id="15bd6-103">Anzahl der Elemente, die dieser Richtlinie zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="15bd6-103">Number of items associated with this policy.</span></span></param>
        <param name="retentionPolicy"><span data-ttu-id="15bd6-104">Aufbewahrung Richtliniendetails.</span><span class="sxs-lookup"><span data-stu-id="15bd6-104">Retention policy details.</span></span></param>
        <summary>
            <span data-ttu-id="15bd6-105">Initialisiert eine neue Instanz der AzureSqlProtectionPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="15bd6-105">Initializes a new instance of the AzureSqlProtectionPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicy" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectionPolicy.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RetentionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15bd6-106">Abrufen oder Festlegen der Beibehaltungsdauer Richtliniendetails.</span><span class="sxs-lookup"><span data-stu-id="15bd6-106">Gets or sets retention policy details.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>