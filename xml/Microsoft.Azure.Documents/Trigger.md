<Type Name="Trigger" FullName="Microsoft.Azure.Documents.Trigger">
  <TypeSignature Language="C#" Value="public class Trigger : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Trigger extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Trigger" />
  <TypeSignature Language="VB.NET" Value="Public Class Trigger&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Trigger = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="86723-101">Stellt einen Trigger in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="86723-101">Represents a trigger in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks> 
            <span data-ttu-id="86723-102">Azure Cosmos-Datenbank unterstützt vor und Post-Trigger, die in JavaScript auf auszuführenden geschriebene erstellt, aktualisiert und gelöscht.</span><span class="sxs-lookup"><span data-stu-id="86723-102">Azure Cosmos DB supports pre and post triggers written in JavaScript to be executed on creates, updates and deletes.</span></span> <span data-ttu-id="86723-103">Weitere Informationen finden Sie in der serverseitige JavaScript-API-Dokumentation.</span><span class="sxs-lookup"><span data-stu-id="86723-103">For additional details, refer to the server-side JavaScript API documentation.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Trigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Trigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="86723-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Trigger" /> Klasse für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="86723-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Trigger" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Trigger.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.Documents.Trigger.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86723-105">Ruft ab oder legt den Text des Triggers für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="86723-105">Gets or sets the body of the trigger for the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="86723-106">der Text des Triggers.</span><span class="sxs-lookup"><span data-stu-id="86723-106">The body of the trigger.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerOperation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.TriggerOperation TriggerOperation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.TriggerOperation TriggerOperation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Trigger.TriggerOperation" />
      <MemberSignature Language="VB.NET" Value="Public Property TriggerOperation As TriggerOperation" />
      <MemberSignature Language="F#" Value="member this.TriggerOperation : Microsoft.Azure.Documents.TriggerOperation with get, set" Usage="Microsoft.Azure.Documents.Trigger.TriggerOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerOperation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.TriggerOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86723-107">Ruft ab oder legt den Vorgang aus, dem der Trigger für den Azure-Cosmos-DB-Dienst zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="86723-107">Gets or sets the operation the trigger is associated with for the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="86723-108">Der Vorgang der Trigger zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="86723-108">The operation the trigger is associated with.</span></span></value>
        <remarks>To be added.</remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Trigger.TriggerOperation" />
      </Docs>
    </Member>
    <Member MemberName="TriggerType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.TriggerType TriggerType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.TriggerType TriggerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Trigger.TriggerType" />
      <MemberSignature Language="VB.NET" Value="Public Property TriggerType As TriggerType" />
      <MemberSignature Language="F#" Value="member this.TriggerType : Microsoft.Azure.Documents.TriggerType with get, set" Usage="Microsoft.Azure.Documents.Trigger.TriggerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="triggerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.TriggerType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86723-109">Abrufen oder Festlegen der Typ des Triggers für den Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="86723-109">Get or set the type of the trigger for the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="86723-110">der Text des Triggers.</span><span class="sxs-lookup"><span data-stu-id="86723-110">The body of the trigger.</span></span></value>
        <remarks>To be added.</remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Trigger.TriggerType" />
      </Docs>
    </Member>
  </Members>
</Type>