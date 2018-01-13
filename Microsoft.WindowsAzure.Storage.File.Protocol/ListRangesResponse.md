<Type Name="ListRangesResponse" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse">
  <TypeSignature Language="C#" Value="public sealed class ListRangesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListRangesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.File.FileRange&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListRangesResponse&#xA;Inherits ResponseParsingBase(Of FileRange)" />
  <TypeSignature Language="F#" Value="type ListRangesResponse = class&#xA;    inherit ResponseParsingBase&lt;FileRange&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.File.FileRange</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2efb6-101">Stellt Methoden zum Analysieren der Antwort aus einem Vorgang können Sie einen Bereich für eine Datei abrufen.</span><span class="sxs-lookup"><span data-stu-id="2efb6-101">Provides methods for parsing the response from an operation to get a range for a file.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListRangesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse" Usage="new Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse stream" />
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
        <param name="stream"><span data-ttu-id="2efb6-102">Der Datenstrom der Bereiche, die analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="2efb6-102">The stream of ranges to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="2efb6-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2efb6-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.FileRange&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of FileRange)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;" Usage="listRangesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2efb6-104">Analysiert die XML-Antwort auf einen Bereich für eine Datei Abrufen eines Vorgangs an.</span><span class="sxs-lookup"><span data-stu-id="2efb6-104">Parses the XML response for an operation to get a range for a file.</span></span>
            </summary>
        <returns><span data-ttu-id="2efb6-105">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2efb6-105">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ranges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt; Ranges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.FileRange&gt; Ranges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse.Ranges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Ranges As IEnumerable(Of FileRange)" />
      <MemberSignature Language="F#" Value="member this.Ranges : seq&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListRangesResponse.Ranges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.FileRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2efb6-106">Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" /> Objekte aus der Antwort.</span><span class="sxs-lookup"><span data-stu-id="2efb6-106">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" /> objects from the response.</span></span>
            </summary>
        <value><span data-ttu-id="2efb6-107">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2efb6-107">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>