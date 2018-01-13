<Type Name="TableResultSegment" FullName="Microsoft.WindowsAzure.Storage.Table.TableResultSegment">
  <TypeSignature Language="C#" Value="public sealed class TableResultSegment : System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableResultSegment extends System.Object implements class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableResultSegment&#xA;Implements IEnumerable(Of CloudTable)" />
  <TypeSignature Language="F#" Value="type TableResultSegment = class&#xA;    interface seq&lt;CloudTable&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="4f9a1-101">Stellt ein Segment dar <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> -Ergebnissen mit fortsetzungsinformationen für paginierungsszenarien.</span><span class="sxs-lookup"><span data-stu-id="4f9a1-101">Represents a segment of <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> results, with continuation information for pagination scenarios.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As TableContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" Usage="Microsoft.WindowsAzure.Storage.Table.TableResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f9a1-102">Ruft das Fortsetzungstoken zum Abrufen des nächsten Segments von <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="4f9a1-102">Gets the continuation token used to retrieve the next segment of <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> results.</span></span> <span data-ttu-id="4f9a1-103">Gibt null zurück, wenn keine weiteren Ergebnisse vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="4f9a1-103">Returns null if there are no more results.</span></span>
            </summary>
        <value><span data-ttu-id="4f9a1-104">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="4f9a1-104">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.WindowsAzure.Storage.Table.CloudTable&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableResultSegment.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of CloudTable)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;" Usage="tableResultSegment.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f9a1-105">Gibt einen Enumerator, der das Segment des durchläuft <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="4f9a1-105">Returns an enumerator that iterates through the segment of <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> results.</span></span> 
            </summary>
        <returns><span data-ttu-id="4f9a1-106">Ein Enumerator, der das Segment des durchläuft <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="4f9a1-106">An enumerator that iterates through the segment of <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> results.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Table.CloudTable&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IList(Of CloudTable)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.TableResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4f9a1-107">Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> Ergebnisse.</span><span class="sxs-lookup"><span data-stu-id="4f9a1-107">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> results.</span></span>
            </summary>
        <value><span data-ttu-id="4f9a1-108">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="4f9a1-108">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableResultSegment.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>