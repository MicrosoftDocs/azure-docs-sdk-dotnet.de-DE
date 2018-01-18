<Type Name="ResponseParsingBase&lt;T&gt;" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class ResponseParsingBase&lt;T&gt; : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ResponseParsingBase`1&lt;T&gt; extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ResponseParsingBase(Of T)&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ResponseParsingBase&lt;'T&gt; = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T"><span data-ttu-id="390b7-101">Der Typ, die analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-101">The type to be parsed.</span></span></typeparam>
    <summary>
            <span data-ttu-id="390b7-102">Stellt eine Basisklasse, die intern, beim Analysieren des XML-Streams aus speicherdienstvorgänge verwendet wird bereit.</span><span class="sxs-lookup"><span data-stu-id="390b7-102">Provides a base class that is used internally to parse XML streams from storage service operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ResponseParsingBase (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt; : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;" Usage="new Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt; stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="390b7-103">Der Stream, der analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-103">The stream to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="390b7-104">Initialisiert eine neue Instanz der ResponseParsingBase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="390b7-104">Initializes a new instance of the ResponseParsingBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="allObjectsParsed">
      <MemberSignature Language="C#" Value="protected bool allObjectsParsed;" />
      <MemberSignature Language="ILAsm" Value=".field family bool allObjectsParsed" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.allObjectsParsed" />
      <MemberSignature Language="VB.NET" Value="Protected allObjectsParsed As Boolean " />
      <MemberSignature Language="F#" Value="val mutable allObjectsParsed : bool" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;.allObjectsParsed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="390b7-105">Gibt an, dass alle analysierbar Objekte verarbeitet wurden.</span><span class="sxs-lookup"><span data-stu-id="390b7-105">Indicates that all parsable objects have been consumed.</span></span> <span data-ttu-id="390b7-106">Dieses Feld ist reserviert und sollte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-106">This field is reserved and should not be used.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="responseParsingBase.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="390b7-107">Führt anwendungsspezifische Aufgaben durch, die mit der Freigabe, der Zurückgabe oder dem Zurücksetzen von nicht verwalteten Ressourcen zusammenhängen.</span><span class="sxs-lookup"><span data-stu-id="390b7-107">Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="responseParsingBase.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <span data-ttu-id="390b7-108"><c>"True"</c> um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="390b7-108"><c>True</c> to release both managed and unmanaged resources; otherwise, <c>false</c>.</span></span></param>
        <summary>
            <span data-ttu-id="390b7-109">Führt anwendungsspezifische Aufgaben im Zusammenhang mit der Freigabe, der Zurückgabe oder dem Zurücksetzen von nicht verwalteten Ressourcen und optional verwaltete Ressourcen zusammenhängen.</span><span class="sxs-lookup"><span data-stu-id="390b7-109">Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources, and optional managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectsToParse">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IEnumerable&lt;T&gt; ObjectsToParse { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ObjectsToParse" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.ObjectsToParse" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ObjectsToParse As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="member this.ObjectsToParse : seq&lt;'T&gt;" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;.ObjectsToParse" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="390b7-110">Ruft die analysierbar Objekte ab.</span><span class="sxs-lookup"><span data-stu-id="390b7-110">Gets the parsable objects.</span></span> <span data-ttu-id="390b7-111">Diese Methode ist reserviert und sollte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-111">This method is reserved and should not be used.</span></span>
            </summary>
        <value><span data-ttu-id="390b7-112">Die Objekte, die analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-112">The objects to parse.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="outstandingObjectsToParse">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IList&lt;T&gt; outstandingObjectsToParse;" />
      <MemberSignature Language="ILAsm" Value=".field family class System.Collections.Generic.IList`1&lt;!T&gt; outstandingObjectsToParse" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.outstandingObjectsToParse" />
      <MemberSignature Language="VB.NET" Value="Protected outstandingObjectsToParse As IList(Of T) " />
      <MemberSignature Language="F#" Value="val mutable outstandingObjectsToParse : System.Collections.Generic.IList&lt;'T&gt;" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;.outstandingObjectsToParse" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="390b7-113">Speichert alle Objekte, die noch nicht analysiert wurde.</span><span class="sxs-lookup"><span data-stu-id="390b7-113">Stores any objects that have not yet been parsed.</span></span> <span data-ttu-id="390b7-114">Dieses Feld ist reserviert und sollte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-114">This field is reserved and should not be used.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;T&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ParseXml () As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ParseXml : unit -&gt; seq&lt;'T&gt;" Usage="responseParsingBase.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="390b7-115">Analysiert die XML-Antwort.</span><span class="sxs-lookup"><span data-stu-id="390b7-115">Parses the XML response.</span></span> <span data-ttu-id="390b7-116">Diese Methode ist reserviert und sollte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-116">This method is reserved and should not be used.</span></span>
            </summary>
        <returns><span data-ttu-id="390b7-117">Eine Auflistung von aufzählbare Objekte.</span><span class="sxs-lookup"><span data-stu-id="390b7-117">A collection of enumerable objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="reader">
      <MemberSignature Language="C#" Value="protected System.Xml.XmlReader reader;" />
      <MemberSignature Language="ILAsm" Value=".field family class System.Xml.XmlReader reader" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.reader" />
      <MemberSignature Language="VB.NET" Value="Protected reader As XmlReader " />
      <MemberSignature Language="F#" Value="val mutable reader : System.Xml.XmlReader" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;'T&gt;.reader" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlReader</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="390b7-118">Der Reader für die Analyse verwendet.</span><span class="sxs-lookup"><span data-stu-id="390b7-118">The reader used for parsing.</span></span> <span data-ttu-id="390b7-119">Dieses Feld ist reserviert und sollte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-119">This field is reserved and should not be used.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Variable">
      <MemberSignature Language="C#" Value="protected void Variable (ref bool consumable);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Variable(bool&amp; consumable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1.Variable(System.Boolean@)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Variable (ByRef consumable As Boolean)" />
      <MemberSignature Language="F#" Value="member this.Variable :  -&gt; unit" Usage="responseParsingBase.Variable consumable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="consumable" Type="System.Boolean&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="consumable">
          <span data-ttu-id="390b7-120"><c>"True"</c> Wenn das Objekt nutzbar ist.</span><span class="sxs-lookup"><span data-stu-id="390b7-120"><c>True</c> when the object is consumable.</span></span></param>
        <summary>
            <span data-ttu-id="390b7-121">Diese Methode ist reserviert und sollte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="390b7-121">This method is reserved and should not be used.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>