<Type Name="RunCommandDocumentBase" FullName="Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase">
  <TypeSignature Language="C#" Value="public class RunCommandDocumentBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RunCommandDocumentBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase" />
  <TypeSignature Language="VB.NET" Value="Public Class RunCommandDocumentBase" />
  <TypeSignature Language="F#" Value="type RunCommandDocumentBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6709d-101">Beschreibt die Eigenschaften einer Metadaten-Befehl ausführen.</span><span class="sxs-lookup"><span data-stu-id="6709d-101">Describes the properties of a Run Command metadata.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandDocumentBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6709d-102">Initialisiert eine neue Instanz der RunCommandDocumentBase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6709d-102">Initializes a new instance of the RunCommandDocumentBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandDocumentBase (string schema, string id, Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes osType, string label, string description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string schema, string id, valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes osType, string label, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.#ctor(System.String,System.String,Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schema As String, id As String, osType As OperatingSystemTypes, label As String, description As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase : string * string * Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes * string * string -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase" Usage="new Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase (schema, id, osType, label, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schema" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes" />
        <Parameter Name="label" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="schema"><span data-ttu-id="6709d-103">Das Schema für den virtuellen Computer ausführen-Befehl.</span><span class="sxs-lookup"><span data-stu-id="6709d-103">The VM run command schema.</span></span></param>
        <param name="id"><span data-ttu-id="6709d-104">Die Befehls-Id des virtuellen Computers ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="6709d-104">The VM run command id.</span></span></param>
        <param name="osType"><span data-ttu-id="6709d-105">Der Typ des Betriebssystems.</span><span class="sxs-lookup"><span data-stu-id="6709d-105">The Operating System type.</span></span> <span data-ttu-id="6709d-106">Folgende Werte sind möglich: "Windows", "Linux"</span><span class="sxs-lookup"><span data-stu-id="6709d-106">Possible values include: 'Windows', 'Linux'</span></span></param>
        <param name="label"><span data-ttu-id="6709d-107">Die Bezeichnung für den virtuellen Computer ausführen-Befehl.</span><span class="sxs-lookup"><span data-stu-id="6709d-107">The VM run command label.</span></span></param>
        <param name="description"><span data-ttu-id="6709d-108">Der virtuelle Computer, die Beschreibung der Befehl ausführen.</span><span class="sxs-lookup"><span data-stu-id="6709d-108">The VM run command description.</span></span></param>
        <summary>
            <span data-ttu-id="6709d-109">Initialisiert eine neue Instanz der RunCommandDocumentBase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6709d-109">Initializes a new instance of the RunCommandDocumentBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6709d-110">Ruft ab oder legt den virtuellen Computer, die Beschreibung der Befehl ausführen.</span><span class="sxs-lookup"><span data-stu-id="6709d-110">Gets or sets the VM run command description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6709d-111">Ruft ab, oder legt Sie den virtuellen Computer führen Sie die Befehls-Id fest.</span><span class="sxs-lookup"><span data-stu-id="6709d-111">Gets or sets the VM run command id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="label")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6709d-112">Abrufen oder Festlegen des virtuellen Computers mit dem Befehl Bezeichnung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="6709d-112">Gets or sets the VM run command label.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OsType : Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6709d-113">Ruft ab oder legt den Betriebssystemtyp.</span><span class="sxs-lookup"><span data-stu-id="6709d-113">Gets or sets the Operating System type.</span></span> <span data-ttu-id="6709d-114">Folgende Werte sind möglich: "Windows", "Linux"</span><span class="sxs-lookup"><span data-stu-id="6709d-114">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schema">
      <MemberSignature Language="C#" Value="public string Schema { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Schema" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Schema" />
      <MemberSignature Language="VB.NET" Value="Public Property Schema As String" />
      <MemberSignature Language="F#" Value="member this.Schema : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Schema" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="$schema")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6709d-115">Abrufen oder Festlegen des virtuellen Computers mit dem Befehl Schema ausführen.</span><span class="sxs-lookup"><span data-stu-id="6709d-115">Gets or sets the VM run command schema.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="runCommandDocumentBase.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6709d-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="6709d-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6709d-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="6709d-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>