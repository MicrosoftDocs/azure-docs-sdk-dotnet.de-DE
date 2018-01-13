<Type Name="MabFileFolderProtectedItemExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo">
  <TypeSignature Language="C#" Value="public class MabFileFolderProtectedItemExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MabFileFolderProtectedItemExtendedInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class MabFileFolderProtectedItemExtendedInfo" />
  <TypeSignature Language="F#" Value="type MabFileFolderProtectedItemExtendedInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8e246-101">Zusätzliche Informationen für das Element gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="8e246-101">Additional information on the backed up item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabFileFolderProtectedItemExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8e246-102">Initialisiert eine neue Instanz der MabFileFolderProtectedItemExtendedInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8e246-102">Initializes a new instance of the MabFileFolderProtectedItemExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabFileFolderProtectedItemExtendedInfo (Nullable&lt;DateTime&gt; lastRefreshedAt = null, Nullable&lt;DateTime&gt; oldestRecoveryPoint = null, Nullable&lt;int&gt; recoveryPointCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRefreshedAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; oldestRecoveryPoint, valuetype System.Nullable`1&lt;int32&gt; recoveryPointCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional lastRefreshedAt As Nullable(Of DateTime) = null, Optional oldestRecoveryPoint As Nullable(Of DateTime) = null, Optional recoveryPointCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo (lastRefreshedAt, oldestRecoveryPoint, recoveryPointCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lastRefreshedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="oldestRecoveryPoint" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryPointCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="lastRefreshedAt"><span data-ttu-id="8e246-103">Wenn die Agentendaten mit Dienst synchronisiert der letzten Ausführung.</span><span class="sxs-lookup"><span data-stu-id="8e246-103">Last time when the agent data synced to service.</span></span></param>
        <param name="oldestRecoveryPoint"><span data-ttu-id="8e246-104">Die älteste Sicherungskopie verfügbar.</span><span class="sxs-lookup"><span data-stu-id="8e246-104">The oldest backup copy available.</span></span></param>
        <param name="recoveryPointCount"><span data-ttu-id="8e246-105">Die Anzahl von Sicherungskopien der Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8e246-105">Number of backup copies associated with the backup item.</span></span></param>
        <summary>
            <span data-ttu-id="8e246-106">Initialisiert eine neue Instanz der MabFileFolderProtectedItemExtendedInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8e246-106">Initializes a new instance of the MabFileFolderProtectedItemExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRefreshedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRefreshedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRefreshedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo.LastRefreshedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRefreshedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRefreshedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo.LastRefreshedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastRefreshedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e246-107">Ruft ab, oder legt Sie zuletzt bei die Agentendaten synchronisiert Dienst fest.</span><span class="sxs-lookup"><span data-stu-id="8e246-107">Gets or sets last time when the agent data synced to service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OldestRecoveryPoint">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OldestRecoveryPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OldestRecoveryPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo.OldestRecoveryPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property OldestRecoveryPoint As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OldestRecoveryPoint : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo.OldestRecoveryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="oldestRecoveryPoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e246-108">Ermittelt oder definiert die älteste Sicherungskopie verfügbar.</span><span class="sxs-lookup"><span data-stu-id="8e246-108">Gets or sets the oldest backup copy available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RecoveryPointCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RecoveryPointCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo.RecoveryPointCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo.RecoveryPointCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e246-109">Ruft ab oder legt die Anzahl von Sicherungskopien der Sichern des Elements zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8e246-109">Gets or sets number of backup copies associated with the backup item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>