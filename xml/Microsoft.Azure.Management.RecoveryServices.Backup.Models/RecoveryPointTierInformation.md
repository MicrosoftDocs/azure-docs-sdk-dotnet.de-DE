<Type Name="RecoveryPointTierInformation" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation">
  <TypeSignature Language="C#" Value="public class RecoveryPointTierInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecoveryPointTierInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class RecoveryPointTierInformation" />
  <TypeSignature Language="F#" Value="type RecoveryPointTierInformation = class" />
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
            <span data-ttu-id="3bbf7-101">Punkt-Tier-Wiederherstellungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="3bbf7-101">Recovery point tier information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryPointTierInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3bbf7-102">Initialisiert eine neue Instanz der RecoveryPointTierInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3bbf7-102">Initializes a new instance of the RecoveryPointTierInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecoveryPointTierInformation (Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType&gt; type = null, Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus&gt; status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType&gt; type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus&gt; status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation.#ctor(System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType},System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As Nullable(Of RecoveryPointTierType) = null, Optional status As Nullable(Of RecoveryPointTierStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType&gt; * Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation (type, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="3bbf7-103">Ebene Wiederherstellungspunkttyp.</span><span class="sxs-lookup"><span data-stu-id="3bbf7-103">Recovery point tier type.</span></span> <span data-ttu-id="3bbf7-104">Folgende Werte sind möglich: "Ungültig", "InstantRP", "HardenedRP"</span><span class="sxs-lookup"><span data-stu-id="3bbf7-104">Possible values include: 'Invalid', 'InstantRP', 'HardenedRP'</span></span></param>
        <param name="status"><span data-ttu-id="3bbf7-105">Wiederherstellung des Status der Ebene.</span><span class="sxs-lookup"><span data-stu-id="3bbf7-105">Recovery point tier status.</span></span> <span data-ttu-id="3bbf7-106">Folgende Werte sind möglich: "Ungültig", "Ungültig", "Deaktiviert", "Deleted"</span><span class="sxs-lookup"><span data-stu-id="3bbf7-106">Possible values include: 'Invalid', 'Valid', 'Disabled', 'Deleted'</span></span></param>
        <summary>
            <span data-ttu-id="3bbf7-107">Initialisiert eine neue Instanz der RecoveryPointTierInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3bbf7-107">Initializes a new instance of the RecoveryPointTierInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of RecoveryPointTierStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bbf7-108">Abrufen oder Festlegen des Ebene Status der Wiederherstellungspunkte.</span><span class="sxs-lookup"><span data-stu-id="3bbf7-108">Gets or sets recovery point tier status.</span></span> <span data-ttu-id="3bbf7-109">Folgende Werte sind möglich: "Ungültig", "Ungültig", "Deaktiviert", "Deleted"</span><span class="sxs-lookup"><span data-stu-id="3bbf7-109">Possible values include: 'Invalid', 'Valid', 'Disabled', 'Deleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of RecoveryPointTierType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierInformation.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointTierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bbf7-110">Ruft ab, oder legt ihn fest Wiederherstellungspunkttyp Ebene.</span><span class="sxs-lookup"><span data-stu-id="3bbf7-110">Gets or sets recovery point tier type.</span></span> <span data-ttu-id="3bbf7-111">Folgende Werte sind möglich: "Ungültig", "InstantRP", "HardenedRP"</span><span class="sxs-lookup"><span data-stu-id="3bbf7-111">Possible values include: 'Invalid', 'InstantRP', 'HardenedRP'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>