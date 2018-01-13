<Type Name="TableResultSegment" FullName="Microsoft.Azure.CosmosDB.Table.TableResultSegment">
  <TypeSignature Language="C#" Value="public sealed class TableResultSegment : System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableResultSegment extends System.Object implements class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.CloudTable&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableResultSegment&#xA;Implements IEnumerable(Of CloudTable)" />
  <TypeSignature Language="F#" Value="type TableResultSegment = class&#xA;    interface seq&lt;CloudTable&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt ein Segment dar <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> -Ergebnissen mit fortsetzungsinformationen für paginierungsszenarien.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As TableContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.Azure.CosmosDB.Table.TableContinuationToken" Usage="Microsoft.Azure.CosmosDB.Table.TableResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Fortsetzungstoken zum Abrufen des nächsten Segments von <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> Ergebnisse. Gibt null zurück, wenn keine weiteren Ergebnisse vorhanden sind.
            </summary>
        <value>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.Azure.CosmosDB.Table.CloudTable&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableResultSegment.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of CloudTable)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;" Usage="tableResultSegment.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt einen Enumerator, der das Segment des durchläuft <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> Ergebnisse. 
            </summary>
        <returns>Ein Enumerator, der das Segment des durchläuft <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> Ergebnisse.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.CloudTable&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IList(Of CloudTable)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> Ergebnisse.
            </summary>
        <value>Eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> Objekte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableResultSegment.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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