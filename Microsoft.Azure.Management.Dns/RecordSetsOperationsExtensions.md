<Type Name="RecordSetsOperationsExtensions" FullName="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecordSetsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecordSetsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecordSetsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecordSetsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet CreateOrUpdate (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet CreateOrUpdate(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * string -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
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
            Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
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
        <summary>
            Erstellt oder aktualisiert einen Datensatz in einer DNS-Zone festgelegt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
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
            Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
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
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Delete(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * string -&gt; unit" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Delete (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="ifMatch" Type="System.String" />
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
            Der Typ des DNS-Eintrags in diesen Datensatz. Zeichnen Sie Sätze von Typ SOA kann nicht gelöscht werden (werden gelöscht, sobald die DNS-Zone gelöscht wird). Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="ifMatch">
            Das Etag des Datensatzes festgelegt. Lassen Sie diesen Wert, um stets aktuelle Ressourceneintragssatz löschen. Geben Sie den letzten gesehen Etag-Wert, um zu verhindern, dass versehentliches Löschen von gleichzeitigen Änderungen.
            </param>
        <summary>
            Löscht einen Datensatz aus einer DNS-Zone festgelegt. Dieser Vorgang kann nicht rückgängig gemacht werden.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.DeleteAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
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
            Der Typ des DNS-Eintrags in diesen Datensatz. Zeichnen Sie Sätze von Typ SOA kann nicht gelöscht werden (werden gelöscht, sobald die DNS-Zone gelöscht wird). Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet Get (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet Get(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Get(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Get (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
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
            Der Typ des DNS-Eintrags in diesen Datensatz. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <summary>
            Ruft einen Ressourceneintragssatz ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; GetAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; GetAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.GetAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
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
            Der Typ des DNS-Eintrags in diesen Datensatz. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
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
    <Member MemberName="ListByDnsZone">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZone (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZone(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZone(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDnsZone (operations As IRecordSetsOperations, resourceGroupName As String, zoneName As String, Optional top As Nullable(Of Integer) = null, Optional recordsetnamesuffix As String = null) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZone : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZone (operations, resourceGroupName, zoneName, top, recordsetnamesuffix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
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
        <param name="top">
            Die maximale Anzahl der zurückzugebenden Datensätze. Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.
            </param>
        <param name="recordsetnamesuffix">
            Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen. Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;
            </param>
        <summary>
            Listet alle Datensatzgruppen in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneAsync (operations, resourceGroupName, zoneName, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByDnsZoneAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
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
        <param name="top">
            Die maximale Anzahl der zurückzugebenden Datensätze. Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.
            </param>
        <param name="recordsetnamesuffix">
            Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen. Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;
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
    <Member MemberName="ListByDnsZoneNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZoneNext (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByDnsZoneNext(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNext(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDnsZoneNext (operations As IRecordSetsOperations, nextPageLink As String) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNext : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Listet alle Datensatzgruppen in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDnsZoneNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneNextAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByDnsZoneNextAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDnsZoneNextAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByDnsZoneNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByDnsZoneNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
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
    <Member MemberName="ListByType">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByType (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByType(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByType(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="F#" Value="static member ListByType : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Nullable&lt;int&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByType (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
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
        <param name="recordType">
            Der Typ der Datensatzgruppen aufgelistet werden. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="top">
            Die maximale Anzahl der zurückzugebenden Datensätze. Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.
            </param>
        <param name="recordsetnamesuffix">
            Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen. Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;
            </param>
        <summary>
            Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Nullable&lt;int&gt; top = null, string recordsetnamesuffix = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, valuetype System.Nullable`1&lt;int32&gt; top, string recordsetnamesuffix, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeAsync (operations, resourceGroupName, zoneName, recordType, top, recordsetnamesuffix, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByTypeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recordsetnamesuffix" Type="System.String" />
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
        <param name="recordType">
            Der Typ der Datensatzgruppen aufgelistet werden. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="top">
            Die maximale Anzahl der zurückzugebenden Datensätze. Wenn nicht angegeben, gibt bis zu 100 Datensatzgruppen zurück.
            </param>
        <param name="recordsetnamesuffix">
            Die suffixbezeichnung des Namen der Datensatzgruppe, die verwendet werden, um den Datensatz Filtern festlegen Enumerationen. Wenn dieser Parameter angegeben wird, gibt die Enumeration nur Datensätze zurück, die mit enden. &lt;RecordSetNameSuffix&gt;
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
    <Member MemberName="ListByTypeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByTypeNext (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; ListByTypeNext(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNext(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByTypeNext (operations As IRecordSetsOperations, nextPageLink As String) As IPage(Of RecordSet)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNext : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Listet die Datensatzgruppen eines angegebenen Typs in einer DNS-Zone.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByTypeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeNextAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt; ListByTypeNextAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNextAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByTypeNextAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.ListByTypeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;ListByTypeNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
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
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Dns.Models.RecordSet Update (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Dns.Models.RecordSet Update(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Update(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string -&gt; Microsoft.Azure.Management.Dns.Models.RecordSet" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.Update (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Models.RecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
        <Parameter Name="ifMatch" Type="System.String" />
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
            Der Typ des DNS-Eintrags in diesen Datensatz. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
            </param>
        <param name="parameters">
            Parameter, die auf den Updatevorgang angegeben werden.
            </param>
        <param name="ifMatch">
            Das Etag des Datensatzes festgelegt. Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben. Geben Sie die letzten gesehen Etag-Wert, um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.
            </param>
        <summary>
            Aktualisiert einen Datensatz in einer DNS-Zone festgelegt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt; UpdateAsync (this Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, Microsoft.Azure.Management.Dns.Models.RecordType recordType, Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Dns.Models.RecordSet&gt; UpdateAsync(class Microsoft.Azure.Management.Dns.IRecordSetsOperations operations, string resourceGroupName, string zoneName, string relativeRecordSetName, valuetype Microsoft.Azure.Management.Dns.Models.RecordType recordType, class Microsoft.Azure.Management.Dns.Models.RecordSet parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Dns.IRecordSetsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Dns.Models.RecordType,Microsoft.Azure.Management.Dns.Models.RecordSet,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Dns.IRecordSetsOperations * string * string * string * Microsoft.Azure.Management.Dns.Models.RecordType * Microsoft.Azure.Management.Dns.Models.RecordSet * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;" Usage="Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions.UpdateAsync (operations, resourceGroupName, zoneName, relativeRecordSetName, recordType, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Dns.RecordSetsOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Dns.Models.RecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Dns.IRecordSetsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="zoneName" Type="System.String" />
        <Parameter Name="relativeRecordSetName" Type="System.String" />
        <Parameter Name="recordType" Type="Microsoft.Azure.Management.Dns.Models.RecordType" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Dns.Models.RecordSet" />
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
            Der Typ des DNS-Eintrags in diesen Datensatz. Folgende Werte sind möglich: "A", "AAAA", "CAA", "CNAME", "MX", "NS", "PTR", "SOA", "SRV", "TXT"
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