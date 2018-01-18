<Type Name="Suggester" FullName="Microsoft.Azure.Search.Models.Suggester">
  <TypeSignature Language="C#" Value="public class Suggester" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi Suggester extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.Suggester" />
  <TypeSignature Language="VB.NET" Value="Public Class Suggester" />
  <TypeSignature Language="F#" Value="type Suggester = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3c972-101">Definiert, wie die Suggest-API-auf eine Gruppe von Feldern im Index angewendet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="3c972-101">Defines how the Suggest API should apply to a group of fields in the index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Suggester ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Suggester.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3c972-102">Initialisiert eine neue Instanz der Suggester-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3c972-102">Initializes a new instance of the Suggester class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Suggester (string name, System.Collections.Generic.IList&lt;string&gt; sourceFields);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; sourceFields) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Suggester.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, sourceFields As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Suggester : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.Suggester" Usage="new Microsoft.Azure.Search.Models.Suggester (name, sourceFields)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sourceFields" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3c972-103">Der Name des suggesters.</span><span class="sxs-lookup"><span data-stu-id="3c972-103">The name of the suggester.</span></span></param>
        <param name="sourceFields"><span data-ttu-id="3c972-104">Die Liste der Feldnamen für die suggesters gilt.</span><span class="sxs-lookup"><span data-stu-id="3c972-104">The list of field names to which the suggester applies.</span></span> <span data-ttu-id="3c972-105">Jedes Feld muss durchsuchbar sein.</span><span class="sxs-lookup"><span data-stu-id="3c972-105">Each field must be searchable.</span></span></param>
        <summary>
            <span data-ttu-id="3c972-106">Initialisiert eine neue Instanz der Suggester-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3c972-106">Initializes a new instance of the Suggester class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Suggester (string name, params string[] sourceFields);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string[] sourceFields) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Suggester.#ctor(System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, ParamArray sourceFields As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Suggester : string * string[] -&gt; Microsoft.Azure.Search.Models.Suggester" Usage="new Microsoft.Azure.Search.Models.Suggester (name, sourceFields)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sourceFields" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3c972-107">Der Name des suggesters.</span><span class="sxs-lookup"><span data-stu-id="3c972-107">The name of the suggester.</span></span></param>
        <param name="sourceFields"><span data-ttu-id="3c972-108">Die Liste der Feldnamen für die suggesters gilt; Jedes Feld muss durchsuchbar sein.</span><span class="sxs-lookup"><span data-stu-id="3c972-108">The list of field names to which the suggester applies; Each field must be searchable.</span></span></param>
        <summary>
            <span data-ttu-id="3c972-109">Initialisiert eine neue Instanz der Suggester-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="3c972-109">Initializes a new instance of the Suggester class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Suggester.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.Suggester.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c972-110">Ruft ab oder legt den Namen des suggesters fest.</span><span class="sxs-lookup"><span data-stu-id="3c972-110">Gets or sets the name of the suggester.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchMode">
      <MemberSignature Language="C#" Value="public static string SearchMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string SearchMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Suggester.SearchMode" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property SearchMode As String" />
      <MemberSignature Language="F#" Value="member this.SearchMode : string" Usage="Microsoft.Azure.Search.Models.Suggester.SearchMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="searchMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c972-111">Ein Wert, der angibt, das die Funktionen des suggesters.</span><span class="sxs-lookup"><span data-stu-id="3c972-111">A value indicating the capabilities of the suggester.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceFields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourceFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourceFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Suggester.SourceFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceFields As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourceFields : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Suggester.SourceFields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceFields")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3c972-112">Ruft ab oder legt die Liste der Feldnamen für die suggesters gilt.</span><span class="sxs-lookup"><span data-stu-id="3c972-112">Gets or sets the list of field names to which the suggester applies.</span></span> <span data-ttu-id="3c972-113">Jedes Feld muss durchsuchbar sein.</span><span class="sxs-lookup"><span data-stu-id="3c972-113">Each field must be searchable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Suggester.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="suggester.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3c972-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3c972-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3c972-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3c972-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>