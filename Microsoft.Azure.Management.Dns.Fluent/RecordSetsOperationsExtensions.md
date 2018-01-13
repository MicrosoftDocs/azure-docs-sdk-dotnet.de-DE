<Type Name="RecordSetsOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecordSetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecordSetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecordSetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecordSetsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für RecordSetsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="relativeRecordSetName">
            Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.
            </param>
        <param name="recordType">
            Der Typ des DNS-Eintrags in diesen Datensatz. Zeichnen Sie Sätze von Typ SOA aktualisiert, aber nicht erstellt werden kann (sie werden erstellt, wenn die DNS-Zone erstellt wird).
            Folgende Werte sind möglich: "A", "AAAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="parameters">
            Parameter für die CreateOrUpdate zur Verfügung gestellt.
            </param>
        <param name="ifMatch">
            Das Etag des Datensatzes festgelegt. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting keine gleichzeitigen geändert werden können.
            </param>
        <param name="ifNoneMatch">
            Legen Sie auf "*" damit wird einen neuen Datensatz erstellt werden festgelegt, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen. Andere Werte werden ignoriert.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert einen Datensatz in einer DNS-Zone festgelegt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="relativeRecordSetName">
            Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.
            </param>
        <param name="recordType">
            Der Typ des DNS-Eintrags in diesen Datensatz. Zeichnen Sie Sätze von Typ SOA kann nicht gelöscht werden (werden gelöscht, sobald die DNS-Zone gelöscht wird). Folgende Werte sind möglich: "A", "AAAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="ifMatch">
            Das Etag des Datensatzes festgelegt. Lassen Sie diesen Wert, um stets aktuelle Ressourceneintragssatz löschen. Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Datensatz aus einer DNS-Zone festgelegt. Dieser Vorgang kann nicht rückgängig gemacht werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; GetAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; GetAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="relativeRecordSetName">
            Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.
            </param>
        <param name="recordType">
            Der Typ des DNS-Eintrags in diesen Datensatz. Folgende Werte sind möglich: "A", "AAAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft einen Ressourceneintragssatz ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneAsync (operations, resourceGroupName, zoneName, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByDnsZoneAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByDnsZoneNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNextAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByDnsZoneNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Datensatzgruppen in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeAsync (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByTypeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="zoneName">To be added.</param>
        <param name="recordType">To be added.</param>
        <param name="top">To be added.</param>
        <param name="recordsetnamesuffix">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeNextAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt; ListByTypeNextAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeNextAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNextAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.ListByTypeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;ListByTypeNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; UpdateAsync (this Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt; UpdateAsync(class Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Fluent.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Fluent.Models.RecordType,Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Fluent.Models.RecordType * Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions.UpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.Fluent.RecordSetsOperationsExtensions/&lt;UpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.Fluent.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Fluent.Models.RecordSetInner" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="zoneName">
            Der Name der DNS-Zone (ohne einen abschließenden Punkt).
            </param>
        <param name="relativeRecordSetName">
            Der Name des Datensatzes festgelegt, relativ zu den Namen der Zone.
            </param>
        <param name="recordType">
            Der Typ des DNS-Eintrags in diesen Datensatz. Folgende Werte sind möglich: "A", "AAAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="parameters">
            Parameter, die auf den Updatevorgang angegeben werden.
            </param>
        <param name="ifMatch">
            Das Etag des Datensatzes festgelegt. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert einen Datensatz in einer DNS-Zone festgelegt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>