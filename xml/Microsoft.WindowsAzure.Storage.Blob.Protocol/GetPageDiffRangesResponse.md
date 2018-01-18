<Type Name="GetPageDiffRangesResponse" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse">
  <TypeSignature Language="C#" Value="public sealed class GetPageDiffRangesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GetPageDiffRangesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GetPageDiffRangesResponse&#xA;Inherits ResponseParsingBase(Of PageDiffRange)" />
  <TypeSignature Language="F#" Value="type GetPageDiffRangesResponse = class&#xA;    inherit ResponseParsingBase&lt;PageDiffRange&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Blob.PageDiffRange</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4cfbf-101">Stellt Methoden zum Analysieren der Antwort aus einem Vorgang, um einen Bereich von unterschiedlichen Seiten für ein Seiten-Blob abzurufen.</span><span class="sxs-lookup"><span data-stu-id="4cfbf-101">Provides methods for parsing the response from an operation to get a range of differing pages for a page blob.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetPageDiffRangesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse stream" />
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
        <param name="stream"><span data-ttu-id="4cfbf-102">Der Datenstrom von Seitenbereichen, die analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="4cfbf-102">The stream of page ranges to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="4cfbf-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageRangesResponse" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4cfbf-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageRangesResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PageDiffRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; PageDiffRanges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; PageDiffRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse.PageDiffRanges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PageDiffRanges As IEnumerable(Of PageDiffRange)" />
      <MemberSignature Language="F#" Value="member this.PageDiffRanges : seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse.PageDiffRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4cfbf-104">Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> Objekte aus der Antwort.</span><span class="sxs-lookup"><span data-stu-id="4cfbf-104">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> objects from the response.</span></span>
            </summary>
        <value><span data-ttu-id="4cfbf-105">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="4cfbf-105">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.GetPageDiffRangesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of PageDiffRange)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;" Usage="getPageDiffRangesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.PageDiffRange&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4cfbf-106">Analysiert die XML-Antwort für einen Vorgang, um einen Bereich von Seiten für ein Seiten-Blob abzurufen.</span><span class="sxs-lookup"><span data-stu-id="4cfbf-106">Parses the XML response for an operation to get a range of pages for a page blob.</span></span>
            </summary>
        <returns><span data-ttu-id="4cfbf-107">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="4cfbf-107">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>