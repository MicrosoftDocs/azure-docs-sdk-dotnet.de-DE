<Type Name="RedirectIncompatibleRowSettings" FullName="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings">
  <TypeSignature Language="C#" Value="public class RedirectIncompatibleRowSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedirectIncompatibleRowSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class RedirectIncompatibleRowSettings" />
  <TypeSignature Language="F#" Value="type RedirectIncompatibleRowSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="84cf6-101">Umleiten der Zeile nicht kompatible Einstellungen</span><span class="sxs-lookup"><span data-stu-id="84cf6-101">Redirect incompatible row settings</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedirectIncompatibleRowSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.#ctor" />
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
            <span data-ttu-id="84cf6-102">Initialisiert eine neue Instanz der RedirectIncompatibleRowSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="84cf6-102">Initializes a new instance of the RedirectIncompatibleRowSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedirectIncompatibleRowSettings (object linkedServiceName, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object path = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object linkedServiceName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.#ctor(System.Object,System.Collections.Generic.IDictionary{System.String,System.Object},System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (linkedServiceName As Object, Optional additionalProperties As IDictionary(Of String, Object) = null, Optional path As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings : obj * System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings" Usage="new Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings (linkedServiceName, additionalProperties, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="linkedServiceName" Type="System.Object" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="path" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="linkedServiceName"><span data-ttu-id="84cf6-103">Name des Azure-Speicher, SAS-Speicher oder Azure Data Lake-Speicher verknüpften Dienst zum Umleiten der Zeile nicht kompatibel.</span><span class="sxs-lookup"><span data-stu-id="84cf6-103">Name of the Azure Storage, Storage SAS, or Azure Data Lake Store linked service used for redirecting incompatible row.</span></span> <span data-ttu-id="84cf6-104">Muss angegeben werden, wenn RedirectIncompatibleRowSettings angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="84cf6-104">Must be specified if redirectIncompatibleRowSettings is specified.</span></span> <span data-ttu-id="84cf6-105">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="84cf6-105">Type: string (or Expression with resultType string).</span></span></param>
        <param name="additionalProperties"><span data-ttu-id="84cf6-106">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="84cf6-106">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="path"><span data-ttu-id="84cf6-107">Der Pfad zum Speichern von Daten aus der inkompatible Zeile umleiten.</span><span class="sxs-lookup"><span data-stu-id="84cf6-107">The path for storing the redirect incompatible row data.</span></span> <span data-ttu-id="84cf6-108">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="84cf6-108">Type: string (or Expression with resultType string).</span></span></param>
        <summary>
            <span data-ttu-id="84cf6-109">Initialisiert eine neue Instanz der RedirectIncompatibleRowSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="84cf6-109">Initializes a new instance of the RedirectIncompatibleRowSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84cf6-110">Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="84cf6-110">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public object LinkedServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property LinkedServiceName As Object" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84cf6-111">Ruft ab, oder legt ihn fest Name des Azure-Speicher, SAS-Speicher oder Azure Data Lake-Speicher verknüpften Dienst zum Umleiten der Zeile nicht kompatibel.</span><span class="sxs-lookup"><span data-stu-id="84cf6-111">Gets or sets name of the Azure Storage, Storage SAS, or Azure Data Lake Store linked service used for redirecting incompatible row.</span></span>
            <span data-ttu-id="84cf6-112">Muss angegeben werden, wenn RedirectIncompatibleRowSettings angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="84cf6-112">Must be specified if redirectIncompatibleRowSettings is specified.</span></span>
            <span data-ttu-id="84cf6-113">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="84cf6-113">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public object Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As Object" />
      <MemberSignature Language="F#" Value="member this.Path : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84cf6-114">Ruft ab oder legt den Pfad zum Speichern von Daten aus der inkompatible Zeile umleiten.</span><span class="sxs-lookup"><span data-stu-id="84cf6-114">Gets or sets the path for storing the redirect incompatible row data.</span></span> <span data-ttu-id="84cf6-115">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="84cf6-115">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.RedirectIncompatibleRowSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="redirectIncompatibleRowSettings.Validate " />
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
            <span data-ttu-id="84cf6-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="84cf6-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="84cf6-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="84cf6-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>