<Type Name="CustomActivity" FullName="Microsoft.Azure.Management.DataFactory.Models.CustomActivity">
  <TypeSignature Language="C#" Value="public class CustomActivity : Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomActivity extends Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.CustomActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomActivity&#xA;Inherits ExecutionActivity" />
  <TypeSignature Language="F#" Value="type CustomActivity = class&#xA;    inherit ExecutionActivity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.ExecutionActivity</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Custom")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5eb6a-101">Typ der benutzerdefinierten Aktivität.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-101">Custom activity type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5eb6a-102">Initialisiert eine neue Instanz der CustomActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-102">Initializes a new instance of the CustomActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomActivity (string name, object command, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName = null, Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy = null, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference resourceLinkedService = null, object folderPath = null, Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject referenceObjects = null, System.Collections.Generic.IDictionary&lt;string,object&gt; extendedProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object command, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; dependsOn, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy policy, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference resourceLinkedService, object folderPath, class Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject referenceObjects, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; extendedProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.#ctor(System.String,System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ActivityDependency},Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference,System.Object,Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, command As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional dependsOn As IList(Of ActivityDependency) = null, Optional linkedServiceName As LinkedServiceReference = null, Optional policy As ActivityPolicy = null, Optional resourceLinkedService As LinkedServiceReference = null, Optional folderPath As Object = null, Optional referenceObjects As CustomActivityReferenceObject = null, Optional extendedProperties As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.CustomActivity : string * obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt; * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference * obj * Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.CustomActivity" Usage="new Microsoft.Azure.Management.DataFactory.Models.CustomActivity (name, command, additionalProperties, description, dependsOn, linkedServiceName, policy, resourceLinkedService, folderPath, referenceObjects, extendedProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="command" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dependsOn" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ActivityDependency&gt;" />
        <Parameter Name="linkedServiceName" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="policy" Type="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
        <Parameter Name="resourceLinkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference" />
        <Parameter Name="folderPath" Type="System.Object" />
        <Parameter Name="referenceObjects" Type="Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject" />
        <Parameter Name="extendedProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5eb6a-103">Der Name der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-103">Activity name.</span></span></param>
        <param name="command"><span data-ttu-id="5eb6a-104">Befehl für die benutzerdefinierte Aktivität Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="5eb6a-104">Command for custom activity Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="5eb6a-105">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="5eb6a-105">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="description"><span data-ttu-id="5eb6a-106">Beschreibung der Aktivität.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-106">Activity description.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="5eb6a-107">Aktivität hängt vom Zustand ab.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-107">Activity depends on condition.</span></span></param>
        <param name="linkedServiceName"><span data-ttu-id="5eb6a-108">Verknüpften Dienst verweisen.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-108">Linked service reference.</span></span></param>
        <param name="policy"><span data-ttu-id="5eb6a-109">"Aktivitätsrichtlinie".</span><span class="sxs-lookup"><span data-stu-id="5eb6a-109">Activity policy.</span></span></param>
        <param name="resourceLinkedService"><span data-ttu-id="5eb6a-110">Dienstverweis der verknüpften Ressource.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-110">Resource linked service reference.</span></span></param>
        <param name="folderPath"><span data-ttu-id="5eb6a-111">Ordnerpfad für die Ressource Dateien Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="5eb6a-111">Folder path for resource files Type: string (or Expression with resultType string).</span></span></param>
        <param name="referenceObjects"><span data-ttu-id="5eb6a-112">Reference-Objekte</span><span class="sxs-lookup"><span data-stu-id="5eb6a-112">Reference objects</span></span></param>
        <param name="extendedProperties"><span data-ttu-id="5eb6a-113">Benutzerdefinierter Eigenschaftenbehälter.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-113">User defined property bag.</span></span> <span data-ttu-id="5eb6a-114">Es gibt keine Einschränkung für den Schlüssel oder Werte, die verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-114">There is no restriction on the keys or values that can be used.</span></span> <span data-ttu-id="5eb6a-115">Der Benutzer angegeben, dass die benutzerdefinierte Aktivität hat die volle Verantwortung zu nutzen und interpretieren den Inhalt definiert.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-115">The user specified custom activity has the full responsibility to consume and interpret the content defined.</span></span></param>
        <summary>
            <span data-ttu-id="5eb6a-116">Initialisiert eine neue Instanz der CustomActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-116">Initializes a new instance of the CustomActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Command">
      <MemberSignature Language="C#" Value="public object Command { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Command" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.Command" />
      <MemberSignature Language="VB.NET" Value="Public Property Command As Object" />
      <MemberSignature Language="F#" Value="member this.Command : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.Command" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.command")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5eb6a-117">Ruft ab oder legt ihn fest-Befehl für die benutzerdefinierte Aktivität Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="5eb6a-117">Gets or sets command for custom activity Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; ExtendedProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; ExtendedProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ExtendedProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.ExtendedProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ExtendedProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.extendedProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5eb6a-118">Ruft ab, oder legt ihn fest definierten Eigenschaftenbehälter für Benutzer.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-118">Gets or sets user defined property bag.</span></span> <span data-ttu-id="5eb6a-119">Es gibt keine Einschränkung für den Schlüssel oder Werte, die verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-119">There is no restriction on the keys or values that can be used.</span></span> <span data-ttu-id="5eb6a-120">Der Benutzer angegeben, dass die benutzerdefinierte Aktivität hat die volle Verantwortung zu nutzen und interpretieren den Inhalt definiert.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-120">The user specified custom activity has the full responsibility to consume and interpret the content defined.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FolderPath">
      <MemberSignature Language="C#" Value="public object FolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.FolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property FolderPath As Object" />
      <MemberSignature Language="F#" Value="member this.FolderPath : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.FolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.folderPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5eb6a-121">Ruft ab oder legt ihn fest Ordnerpfad für Ressourcendateien Typ: Zeichenfolge (oder einen Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="5eb6a-121">Gets or sets folder path for resource files Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReferenceObjects">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject ReferenceObjects { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject ReferenceObjects" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ReferenceObjects" />
      <MemberSignature Language="VB.NET" Value="Public Property ReferenceObjects As CustomActivityReferenceObject" />
      <MemberSignature Language="F#" Value="member this.ReferenceObjects : Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ReferenceObjects" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.referenceObjects")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.CustomActivityReferenceObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5eb6a-122">Ruft ab oder legt ihn fest Verweisobjekte</span><span class="sxs-lookup"><span data-stu-id="5eb6a-122">Gets or sets reference objects</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceLinkedService">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ResourceLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference ResourceLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ResourceLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceLinkedService As LinkedServiceReference" />
      <MemberSignature Language="F#" Value="member this.ResourceLinkedService : Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CustomActivity.ResourceLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.resourceLinkedService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.LinkedServiceReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5eb6a-123">Ruft ab, oder legt ihn fest Dienstverweis Ressource verknüpft.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-123">Gets or sets resource linked service reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CustomActivity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="customActivity.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5eb6a-124">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5eb6a-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5eb6a-125">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5eb6a-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>