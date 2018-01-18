<Type Name="ExternalChildResourcesCached&lt;FluentModelTImpl,IFluentModelT,InnerModelT,IParentT,ParentImplT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached&lt;FluentModelTImpl,IFluentModelT,InnerModelT,IParentT,ParentImplT&gt;">
  <TypeSignature Language="C#" Value="public abstract class ExternalChildResourcesCached&lt;FluentModelTImpl,IFluentModelT,InnerModelT,IParentT,ParentImplT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourceCollection&lt;FluentModelTImpl,IFluentModelT,InnerModelT,IParentT,ParentImplT&gt; where FluentModelTImpl : ExternalChildResource&lt;IFluentModelT,InnerModelT,IParentT,ParentImplT&gt;, IFluentModelT where IFluentModelT : class, IExternalChildResource&lt;IFluentModelT,IParentT&gt; where ParentImplT : IParentT" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ExternalChildResourcesCached`5&lt;(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4&lt;!IFluentModelT, !InnerModelT, !IParentT, !ParentImplT&gt;, !IFluentModelT) FluentModelTImpl, class (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;!IFluentModelT, !IParentT&gt;) IFluentModelT, InnerModelT, IParentT, (!IParentT) ParentImplT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourceCollection`5&lt;!FluentModelTImpl, !IFluentModelT, !InnerModelT, !IParentT, !ParentImplT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ExternalChildResourcesCached(Of FluentModelTImpl, IFluentModelT, InnerModelT, IParentT, ParentImplT)&#xA;Inherits ExternalChildResourceCollection(Of FluentModelTImpl, IFluentModelT, InnerModelT, IParentT, ParentImplT)" />
  <TypeSignature Language="F#" Value="type ExternalChildResourcesCached&lt;'FluentModelTImpl, 'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelTImpl :&gt; ExternalChildResource&lt;'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT&gt; and 'FluentModelTImpl :&gt; 'IFluentModelT and 'IFluentModelT : null and 'IFluentModelT :&gt; IExternalChildResource&lt;'IFluentModelT, 'IParentT&gt;)&gt; = class&#xA;    inherit ExternalChildResourceCollection&lt;'FluentModelTImpl, 'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelTImpl :&gt; ExternalChildResource&lt;'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT&gt; and 'FluentModelTImpl :&gt; 'IFluentModelT and 'IFluentModelT : null and 'IFluentModelT :&gt; IExternalChildResource&lt;'IFluentModelT, 'IParentT&gt;)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentModelTImpl">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;IFluentModelT,InnerModelT,IParentT,ParentImplT&gt;</BaseTypeName>
        <BaseTypeName>IFluentModelT</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="IFluentModelT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;IFluentModelT,IParentT&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="InnerModelT" />
    <TypeParameter Name="IParentT" />
    <TypeParameter Name="ParentImplT">
      <Constraints>
        <BaseTypeName>IParentT</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourceCollection&lt;FluentModelTImpl,IFluentModelT,InnerModelT,IParentT,ParentImplT&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="FluentModelTImpl">FluentModelTImpl</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IFluentModelT">IFluentModelT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="InnerModelT">InnerModelT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IParentT">IParentT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="ParentImplT">ParentImplT</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="FluentModelTImpl">To be added.</typeparam>
    <typeparam name="IFluentModelT">To be added.</typeparam>
    <typeparam name="InnerModelT">To be added.</typeparam>
    <typeparam name="IParentT">To be added.</typeparam>
    <typeparam name="ParentImplT">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ExternalChildResourcesCached (ParentImplT parent, string childResourceName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(!ParentImplT parent, string childResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.#ctor(`4,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (parent As ParentImplT, childResourceName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached&lt;'FluentModelTImpl, 'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelTImpl :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT&gt; and 'FluentModelTImpl :&gt; 'IFluentModelT and 'IFluentModelT : null and 'IFluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'IFluentModelT, 'IParentT&gt;)&gt; : 'ParentImplT * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached&lt;'FluentModelTImpl, 'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelTImpl :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT&gt; and 'FluentModelTImpl :&gt; 'IFluentModelT and 'IFluentModelT : null and 'IFluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'IFluentModelT, 'IParentT&gt;)&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached&lt;'FluentModelTImpl, 'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelTImpl :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT&gt; and 'FluentModelTImpl :&gt; 'IFluentModelT and 'IFluentModelT : null and 'IFluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'IFluentModelT, 'IParentT&gt;)&gt; (parent, childResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="parent" Type="ParentImplT" />
        <Parameter Name="childResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parent"><span data-ttu-id="a3eac-101">das übergeordnete Element Azure-Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-101">the parent Azure resource</span></span></param>
        <param name="childResourceName"><span data-ttu-id="a3eac-102">der Name der untergeordneten Ressourcen</span><span class="sxs-lookup"><span data-stu-id="a3eac-102">the child resource name</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-103">Erstellt eine neue ExternalChildResourcesCached an.</span><span class="sxs-lookup"><span data-stu-id="a3eac-103">Creates a new ExternalChildResourcesCached.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddChildResource">
      <MemberSignature Language="C#" Value="protected void AddChildResource (FluentModelTImpl childResource);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void AddChildResource(!FluentModelTImpl childResource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.AddChildResource(`0)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub AddChildResource (childResource As FluentModelTImpl)" />
      <MemberSignature Language="F#" Value="member this.AddChildResource : 'FluentModelTImpl -&gt; unit" Usage="externalChildResourcesCached.AddChildResource childResource" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="childResource" Type="FluentModelTImpl" />
      </Parameters>
      <Docs>
        <param name="childResource"><span data-ttu-id="a3eac-104">ChildResource die externen untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-104">childResource the external child resource</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-105">Eine Ressource externen untergeordnetes Element hinzugefügt der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="a3eac-105">Adds an external child resource to the collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheCollection">
      <MemberSignature Language="C#" Value="protected void CacheCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void CacheCollection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.CacheCollection" />
      <MemberSignature Language="VB.NET" Value="Protected Sub CacheCollection ()" />
      <MemberSignature Language="F#" Value="member this.CacheCollection : unit -&gt; unit" Usage="externalChildResourcesCached.CacheCollection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a3eac-106">Initialisiert die Auflistung der externen untergeordnete Ressource.</span><span class="sxs-lookup"><span data-stu-id="a3eac-106">Initializes the external child resource collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAfterCommit">
      <MemberSignature Language="C#" Value="protected override bool ClearAfterCommit ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool ClearAfterCommit() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.ClearAfterCommit" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ClearAfterCommit () As Boolean" />
      <MemberSignature Language="F#" Value="override this.ClearAfterCommit : unit -&gt; bool" Usage="externalChildResourcesCached.ClearAfterCommit " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collection">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IDictionary&lt;string,FluentModelTImpl&gt; Collection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, !FluentModelTImpl&gt; Collection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.Collection" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Collection As IDictionary(Of String, FluentModelTImpl)" />
      <MemberSignature Language="F#" Value="member this.Collection : System.Collections.Generic.IDictionary&lt;string, 'FluentModelTImpl (requires 'FluentModelTImpl :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT&gt; and 'FluentModelTImpl :&gt; 'IFluentModelT)&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached&lt;'FluentModelTImpl, 'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelTImpl :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT&gt; and 'FluentModelTImpl :&gt; 'IFluentModelT and 'IFluentModelT : null and 'IFluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'IFluentModelT, 'IParentT&gt;)&gt;.Collection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,FluentModelTImpl&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="a3eac-107">die untergeordnete Ressource Auflistung als nur-Lese Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="a3eac-107">the child resource collection as a read-only dictionary.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListChildResources">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IList&lt;FluentModelTImpl&gt; ListChildResources ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;!FluentModelTImpl&gt; ListChildResources() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.ListChildResources" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ListChildResources () As IList(Of FluentModelTImpl)" />
      <MemberSignature Language="F#" Value="abstract member ListChildResources : unit -&gt; System.Collections.Generic.IList&lt;'FluentModelTImpl (requires 'FluentModelTImpl :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'IFluentModelT, 'InnerModelT, 'IParentT, #'IParentT&gt; and 'FluentModelTImpl :&gt; 'IFluentModelT)&gt;" Usage="externalChildResourcesCached.ListChildResources " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;FluentModelTImpl&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a3eac-108">Ruft die Liste der externen untergeordneten Ressourcen ab.</span><span class="sxs-lookup"><span data-stu-id="a3eac-108">Gets the list of external child resources.</span></span>
            </summary>
        <returns><span data-ttu-id="a3eac-109">die Liste der untergeordneten externe Ressourcen</span><span class="sxs-lookup"><span data-stu-id="a3eac-109">the list of external child resources</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewChildResource">
      <MemberSignature Language="C#" Value="protected abstract FluentModelTImpl NewChildResource (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance !FluentModelTImpl NewChildResource(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.NewChildResource(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function NewChildResource (name As String) As FluentModelTImpl" />
      <MemberSignature Language="F#" Value="abstract member NewChildResource : string -&gt; 'FluentModelTImpl" Usage="externalChildResourcesCached.NewChildResource name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentModelTImpl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3eac-110">der Name für die neue untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-110">the name for the new child resource</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-111">Ruft eine neue externe untergeordnete Ressource Modellinstanz.</span><span class="sxs-lookup"><span data-stu-id="a3eac-111">Gets a new external child resource model instance.</span></span>
            </summary>
        <returns><span data-ttu-id="a3eac-112">die neue untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-112">the new child resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareDefine">
      <MemberSignature Language="C#" Value="protected FluentModelTImpl PrepareDefine (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !FluentModelTImpl PrepareDefine(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.PrepareDefine(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function PrepareDefine (name As String) As FluentModelTImpl" />
      <MemberSignature Language="F#" Value="member this.PrepareDefine : string -&gt; 'FluentModelTImpl" Usage="externalChildResourcesCached.PrepareDefine name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentModelTImpl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3eac-113">der Name für die neue externe untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-113">the name for the new external child resource</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-114">Vorbereiten Sie für die Definition eine neue externe untergeordnete Ressource.</span><span class="sxs-lookup"><span data-stu-id="a3eac-114">Prepare for definition of a new external child resource.</span></span>
            </summary>
        <returns><span data-ttu-id="a3eac-115">die untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-115">the child resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareDefine">
      <MemberSignature Language="C#" Value="protected FluentModelTImpl PrepareDefine (string name, string key);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !FluentModelTImpl PrepareDefine(string name, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.PrepareDefine(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function PrepareDefine (name As String, key As String) As FluentModelTImpl" />
      <MemberSignature Language="F#" Value="member this.PrepareDefine : string * string -&gt; 'FluentModelTImpl" Usage="externalChildResourcesCached.PrepareDefine (name, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentModelTImpl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3eac-116">der Name für die neue externe untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-116">the name for the new external child resource</span></span></param>
        <param name="key"><span data-ttu-id="a3eac-117">der Schlüssel für die neue externe untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-117">the key for the new external child resource</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-118">Vorbereiten Sie für die Definition eine neue externe untergeordnete Ressource.</span><span class="sxs-lookup"><span data-stu-id="a3eac-118">Prepare for definition of a new external child resource.</span></span>
            </summary>
        <returns><span data-ttu-id="a3eac-119">die untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-119">the child resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareRemove">
      <MemberSignature Language="C#" Value="protected void PrepareRemove (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void PrepareRemove(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.PrepareRemove(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub PrepareRemove (name As String)" />
      <MemberSignature Language="F#" Value="member this.PrepareRemove : string -&gt; unit" Usage="externalChildResourcesCached.PrepareRemove name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3eac-120">der Name der externen untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-120">the name of the external child resource</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-121">Markieren Sie eine externe untergeordnete Ressource mit dem angegebenen Namen, die entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="a3eac-121">Mark an external child resource with given name as to be removed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareRemove">
      <MemberSignature Language="C#" Value="protected void PrepareRemove (string name, string key);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void PrepareRemove(string name, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.PrepareRemove(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub PrepareRemove (name As String, key As String)" />
      <MemberSignature Language="F#" Value="member this.PrepareRemove : string * string -&gt; unit" Usage="externalChildResourcesCached.PrepareRemove (name, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3eac-122">der Name der externen untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-122">the name of the external child resource</span></span></param>
        <param name="key"><span data-ttu-id="a3eac-123">der Schlüssel für die externe untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-123">the key for the external child resource</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-124">Markieren Sie eine externe untergeordnete Ressource mit dem angegebenen Namen, die entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="a3eac-124">Mark an external child resource with given name as to be removed.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareUpdate">
      <MemberSignature Language="C#" Value="protected FluentModelTImpl PrepareUpdate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !FluentModelTImpl PrepareUpdate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.PrepareUpdate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function PrepareUpdate (name As String) As FluentModelTImpl" />
      <MemberSignature Language="F#" Value="member this.PrepareUpdate : string -&gt; 'FluentModelTImpl" Usage="externalChildResourcesCached.PrepareUpdate name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentModelTImpl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3eac-125">der Name der externen untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-125">the name of the external child resource</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-126">Vorbereiten Sie für ein Update des externen untergeordnete Ressource.</span><span class="sxs-lookup"><span data-stu-id="a3eac-126">Prepare for an external child resource update.</span></span>
            </summary>
        <returns><span data-ttu-id="a3eac-127">die externe untergeordnete Ressource aktualisiert werden</span><span class="sxs-lookup"><span data-stu-id="a3eac-127">the external child resource to be updated</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareUpdate">
      <MemberSignature Language="C#" Value="protected FluentModelTImpl PrepareUpdate (string name, string key);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance !FluentModelTImpl PrepareUpdate(string name, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.PrepareUpdate(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function PrepareUpdate (name As String, key As String) As FluentModelTImpl" />
      <MemberSignature Language="F#" Value="member this.PrepareUpdate : string * string -&gt; 'FluentModelTImpl" Usage="externalChildResourcesCached.PrepareUpdate (name, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentModelTImpl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a3eac-128">der Name der externen untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-128">the name of the external child resource</span></span></param>
        <param name="key"><span data-ttu-id="a3eac-129">der Schlüssel für die externe untergeordnete Ressource</span><span class="sxs-lookup"><span data-stu-id="a3eac-129">the key for the external child resource</span></span></param>
        <summary>
            <span data-ttu-id="a3eac-130">Vorbereiten Sie für ein Update des externen untergeordnete Ressource.</span><span class="sxs-lookup"><span data-stu-id="a3eac-130">Prepare for an external child resource update.</span></span>
            </summary>
        <returns><span data-ttu-id="a3eac-131">die externe untergeordnete Ressource aktualisiert werden</span><span class="sxs-lookup"><span data-stu-id="a3eac-131">the external child resource to be updated</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Refresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResourcesCached`5.Refresh" />
      <MemberSignature Language="VB.NET" Value="Public Sub Refresh ()" />
      <MemberSignature Language="F#" Value="member this.Refresh : unit -&gt; unit" Usage="externalChildResourcesCached.Refresh " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a3eac-132">Aktualisieren Sie die Auflistung ein.</span><span class="sxs-lookup"><span data-stu-id="a3eac-132">Refresh the collection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>