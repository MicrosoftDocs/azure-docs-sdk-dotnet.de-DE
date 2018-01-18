<Type Name="MemberAccessNode" FullName="Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode">
  <TypeSignature Language="C#" Value="public sealed class MemberAccessNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MemberAccessNode extends Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MemberAccessNode&#xA;Inherits QueryNode" />
  <TypeSignature Language="F#" Value="type MemberAccessNode = class&#xA;    inherit QueryNode" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="46b39-101">Knoten, die einen Zugriff auf einen Memberwert darstellt.</span><span class="sxs-lookup"><span data-stu-id="46b39-101">Node representing an access to a member value.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MemberAccessNode (Microsoft.WindowsAzure.MobileServices.Query.QueryNode instance, string memberName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.Query.QueryNode instance, string memberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode.#ctor(Microsoft.WindowsAzure.MobileServices.Query.QueryNode,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (instance As QueryNode, memberName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode : Microsoft.WindowsAzure.MobileServices.Query.QueryNode * string -&gt; Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode" Usage="new Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode (instance, memberName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="instance" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />
        <Parameter Name="memberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="instance"><span data-ttu-id="46b39-102">Die Instanz auf Member zugreifen.</span><span class="sxs-lookup"><span data-stu-id="46b39-102">Instance to access member of.</span></span></param>
        <param name="memberName"><span data-ttu-id="46b39-103">Der Elementname auf.</span><span class="sxs-lookup"><span data-stu-id="46b39-103">The member name to access.</span></span></param>
        <summary>
            <span data-ttu-id="46b39-104">Initialisiert eine Instanz von<see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode" /></span><span class="sxs-lookup"><span data-stu-id="46b39-104">Initializes an instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Accept&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T Accept&lt;T&gt; (Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt; visitor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T Accept&lt;T&gt;(class Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1&lt;!!T&gt; visitor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode.Accept``1(Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Accept(Of T) (visitor As QueryNodeVisitor(Of T)) As T" />
      <MemberSignature Language="F#" Value="override this.Accept : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;'T&gt; -&gt; 'T" Usage="memberAccessNode.Accept visitor" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="visitor" Type="Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="46b39-105">Der Typ, den der Besucher zurückgibt, nachdem er dieses Token besucht hat.</span><span class="sxs-lookup"><span data-stu-id="46b39-105">Type that the visitor will return after visiting this token.</span></span></typeparam>
        <param name="visitor"><span data-ttu-id="46b39-106">Eine Implementierung der Besucherschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="46b39-106">An implementation of the visitor interface.</span></span></param>
        <summary>
            <span data-ttu-id="46b39-107">Akzeptiert das Durchlaufen der Struktur von <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" />s durch einen <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />.</span><span class="sxs-lookup"><span data-stu-id="46b39-107">Accept a <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" /> to walk a tree of <see cref="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNode" />s.</span></span>
            </summary>
        <returns><span data-ttu-id="46b39-108">Ein Objekt, dessen Typ durch den Typparameter des Besuchers bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="46b39-108">An object whose type is determined by the type parameter of the visitor.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Instance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Query.QueryNode Instance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Query.QueryNode Instance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode.Instance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Instance As QueryNode" />
      <MemberSignature Language="F#" Value="member this.Instance : Microsoft.WindowsAzure.MobileServices.Query.QueryNode" Usage="Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode.Instance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46b39-109">Die Instanz auf Member zugreifen.</span><span class="sxs-lookup"><span data-stu-id="46b39-109">Instance to access member of.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public override Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Kind As QueryNodeKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind" Usage="Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Query.QueryNodeKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46b39-110">Ruft die Art des Abfrageknotens ab.</span><span class="sxs-lookup"><span data-stu-id="46b39-110">Gets the kind of the query node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemberName">
      <MemberSignature Language="C#" Value="public string MemberName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MemberName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode.MemberName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MemberName As String" />
      <MemberSignature Language="F#" Value="member this.MemberName : string" Usage="Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode.MemberName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46b39-111">Ruft den Zugriff auf den Elementnamen ab.</span><span class="sxs-lookup"><span data-stu-id="46b39-111">Gets the member name to access.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>