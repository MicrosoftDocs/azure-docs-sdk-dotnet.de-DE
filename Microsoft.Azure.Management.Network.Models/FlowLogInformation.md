<Type Name="FlowLogInformation" FullName="Microsoft.Azure.Management.Network.Models.FlowLogInformation">
  <TypeSignature Language="C#" Value="public class FlowLogInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FlowLogInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.FlowLogInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class FlowLogInformation" />
  <TypeSignature Language="F#" Value="type FlowLogInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="26dd6-101">Informationen über die Konfiguration des Protokolls für Datenfluss.</span><span class="sxs-lookup"><span data-stu-id="26dd6-101">Information on the configuration of flow log.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FlowLogInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.FlowLogInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="26dd6-102">Initialisiert eine neue Instanz der FlowLogInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="26dd6-102">Initializes a new instance of the FlowLogInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FlowLogInformation (string targetResourceId, string storageId, bool enabled, Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters retentionPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string storageId, bool enabled, class Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters retentionPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.FlowLogInformation.#ctor(System.String,System.String,System.Boolean,Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, storageId As String, enabled As Boolean, Optional retentionPolicy As RetentionPolicyParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.FlowLogInformation : string * string * bool * Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters -&gt; Microsoft.Azure.Management.Network.Models.FlowLogInformation" Usage="new Microsoft.Azure.Management.Network.Models.FlowLogInformation (targetResourceId, storageId, enabled, retentionPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="storageId" Type="System.String" />
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters" />
      </Parameters>
      <Docs>
        <param name="targetResourceId"><span data-ttu-id="26dd6-103">Die ID der Ressource für die Datenfluss-Protokollierung zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="26dd6-103">The ID of the resource to configure for flow logging.</span></span></param>
        <param name="storageId"><span data-ttu-id="26dd6-104">Die ID des Speicherkontos, das die zum Speichern der Datenfluss verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="26dd6-104">ID of the storage account which is used to store the flow log.</span></span></param>
        <param name="enabled"><span data-ttu-id="26dd6-105">Flag zum Aktivieren/Deaktivieren flow Protokollierung.</span><span class="sxs-lookup"><span data-stu-id="26dd6-105">Flag to enable/disable flow logging.</span></span></param>
        <param name="retentionPolicy">To be added.</param>
        <summary>
            <span data-ttu-id="26dd6-106">Initialisiert eine neue Instanz der FlowLogInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="26dd6-106">Initializes a new instance of the FlowLogInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.FlowLogInformation.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Network.Models.FlowLogInformation.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26dd6-107">Ruft ab, oder legt ihn fest-Flag aktiviert bzw. deaktiviert die Protokollierung der Datenfluss.</span><span class="sxs-lookup"><span data-stu-id="26dd6-107">Gets or sets flag to enable/disable flow logging.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.FlowLogInformation.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicyParameters" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters with get, set" Usage="Microsoft.Azure.Management.Network.Models.FlowLogInformation.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RetentionPolicyParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageId">
      <MemberSignature Language="C#" Value="public string StorageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.FlowLogInformation.StorageId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageId As String" />
      <MemberSignature Language="F#" Value="member this.StorageId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.FlowLogInformation.StorageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26dd6-108">Ermittelt oder definiert die ID des Speicherkontos, das die zum Speichern der Datenfluss verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="26dd6-108">Gets or sets ID of the storage account which is used to store the flow log.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.FlowLogInformation.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.FlowLogInformation.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26dd6-109">Ruft ab oder legt die ID der Ressource für die Datenfluss-Protokollierung zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="26dd6-109">Gets or sets the ID of the resource to configure for flow logging.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.FlowLogInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="flowLogInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="26dd6-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="26dd6-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="26dd6-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="26dd6-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>