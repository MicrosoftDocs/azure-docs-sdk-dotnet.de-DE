<Type Name="Edge" FullName="Microsoft.Azure.Graphs.Elements.Edge">
  <TypeSignature Language="C#" Value="public class Edge" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Edge extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.Elements.Edge" />
  <TypeSignature Language="VB.NET" Value="Public Class Edge" />
  <TypeSignature Language="F#" Value="type Edge = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Graphs.Elements.EdgeConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="85c9e-101">Der Speichercontainer für Edge-Daten.</span><span class="sxs-lookup"><span data-stu-id="85c9e-101">Storage container for edge data.</span></span>
            <span data-ttu-id="85c9e-102">Unterstützt die Deserialisierung von GraphSON-Format.</span><span class="sxs-lookup"><span data-stu-id="85c9e-102">Supports deserialization from GraphSON format.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Edge ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Graphs.Elements.Edge" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="85c9e-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Graphs.Elements.Edge" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.Property&gt; GetProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Graphs.Elements.Property&gt; GetProperties() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.GetProperties" />
      <MemberSignature Language="VB.NET" Value="Public Iterator Function GetProperties () As IEnumerable(Of Property)" />
      <MemberSignature Language="F#" Value="member this.GetProperties : unit -&gt; seq&lt;Microsoft.Azure.Graphs.Elements.Property&gt;" Usage="edge.GetProperties " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.IteratorStateMachine(typeof(Microsoft.Azure.Graphs.Elements.Edge/&lt;GetProperties&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Graphs.Elements.Property&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-104">Ruft alle Eigenschaften auf den Rand an.</span><span class="sxs-lookup"><span data-stu-id="85c9e-104">Gets all the propeties on the edge.</span></span>
            </summary>
        <returns><span data-ttu-id="85c9e-105">Aufzählbare Eigenschaften Kanten.</span><span class="sxs-lookup"><span data-stu-id="85c9e-105">Enumerable of the edges properties.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.Elements.Property GetProperty (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Graphs.Elements.Property GetProperty(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.GetProperty(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProperty (key As String) As Property" />
      <MemberSignature Language="F#" Value="member this.GetProperty : string -&gt; Microsoft.Azure.Graphs.Elements.Property" Usage="edge.GetProperty key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.Elements.Property</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="85c9e-106">Der Schlüssel der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="85c9e-106">The key of the property.</span></span></param>
        <summary>
            <span data-ttu-id="85c9e-107">Ruft eine Eigenschaft auf den Rand, den Schlüssel erhält.</span><span class="sxs-lookup"><span data-stu-id="85c9e-107">Gets a property on the edge, given the property key.</span></span>
            </summary>
        <returns><span data-ttu-id="85c9e-108">Eigenschaft, die Übereinstimmungen zu <paramref name="key" />.</span><span class="sxs-lookup"><span data-stu-id="85c9e-108">Property that matches to <paramref name="key" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public object Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Object" />
      <MemberSignature Language="F#" Value="member this.Id : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-109">Ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="85c9e-109">Gets or sets the identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="85c9e-110">Der Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="85c9e-110">The identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InVertexId">
      <MemberSignature Language="C#" Value="public object InVertexId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object InVertexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.InVertexId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InVertexId As Object" />
      <MemberSignature Language="F#" Value="member this.InVertexId : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.InVertexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-111">Ruft ab oder legt ihn fest in Vertex Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="85c9e-111">Gets or sets the in vertex identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="85c9e-112">Die Vertex-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="85c9e-112">The in vertex identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InVertexLabel">
      <MemberSignature Language="C#" Value="public string InVertexLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InVertexLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.InVertexLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InVertexLabel As String" />
      <MemberSignature Language="F#" Value="member this.InVertexLabel : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.InVertexLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-113">Ruft ab oder legt ihn fest in Vertex Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="85c9e-113">Gets or sets the in vertex label.</span></span>
            </summary>
        <value>
            <span data-ttu-id="85c9e-114">Die Vertex-Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="85c9e-114">The in vertex label.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.Label" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-115">Ruft ab oder legt die Bezeichnung fest.</span><span class="sxs-lookup"><span data-stu-id="85c9e-115">Gets or sets the label.</span></span>
            </summary>
        <value>
            <span data-ttu-id="85c9e-116">Die Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="85c9e-116">The label.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutVertexId">
      <MemberSignature Language="C#" Value="public object OutVertexId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object OutVertexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.OutVertexId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutVertexId As Object" />
      <MemberSignature Language="F#" Value="member this.OutVertexId : obj" Usage="Microsoft.Azure.Graphs.Elements.Edge.OutVertexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-117">Ruft ab oder legt ihn fest Out Vertex-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="85c9e-117">Gets or sets the out vertex identifier.</span></span>
            </summary>
        <value>
            <span data-ttu-id="85c9e-118">Die out-Vertex-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="85c9e-118">The out vertex identifier.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutVertexLabel">
      <MemberSignature Language="C#" Value="public string OutVertexLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutVertexLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.Elements.Edge.OutVertexLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutVertexLabel As String" />
      <MemberSignature Language="F#" Value="member this.OutVertexLabel : string" Usage="Microsoft.Azure.Graphs.Elements.Edge.OutVertexLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-119">Ruft ab oder legt ihn fest Out Vertex-Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="85c9e-119">Gets or sets the out vertex label.</span></span>
            </summary>
        <value>
            <span data-ttu-id="85c9e-120">Die Out Vertex-Bezeichnung.</span><span class="sxs-lookup"><span data-stu-id="85c9e-120">The out vertex label.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.Elements.Edge.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="edge.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="85c9e-121">Diese Instanz wird überprüft.</span><span class="sxs-lookup"><span data-stu-id="85c9e-121">Validates this instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="85c9e-122">Edge muss eine gültige ID oder Edge muss eine gültige Bezeichnung aufweisen.</span><span class="sxs-lookup"><span data-stu-id="85c9e-122">Edge must have a valid Id. or Edge must have a valid Label.</span></span>
            </exception>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="85c9e-123">Edge muss InVertexId angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="85c9e-123">Edge must specify InVertexId.</span></span>
            <span data-ttu-id="85c9e-124">oder Edge muss OutVertexId angeben.</span><span class="sxs-lookup"><span data-stu-id="85c9e-124">or Edge must specify OutVertexId.</span></span>
            <span data-ttu-id="85c9e-125">oder Edge muss InVertexLabel angeben.</span><span class="sxs-lookup"><span data-stu-id="85c9e-125">or Edge must specify InVertexLabel.</span></span>
            <span data-ttu-id="85c9e-126">oder Edge muss OutVertexLabel angeben.</span><span class="sxs-lookup"><span data-stu-id="85c9e-126">or Edge must specify OutVertexLabel.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>