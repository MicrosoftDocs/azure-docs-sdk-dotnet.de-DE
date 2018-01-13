<Type Name="ShardMapManager" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager">
  <TypeSignature Language="C#" Value="public sealed class ShardMapManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ShardMapManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ShardMapManager" />
  <TypeSignature Language="F#" Value="type ShardMapManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt den Einstiegspunkt für die Erstellung, Verwaltung und Suchvorgänge für shardzuordnungen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateListShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt; CreateListShardMap&lt;TKey&gt; (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1&lt;!!TKey&gt; CreateListShardMap&lt;TKey&gt;(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.CreateListShardMap``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateListShardMap(Of TKey) (shardMapName As String) As ListShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.CreateListShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;'Key&gt;" Usage="shardMapManager.CreateListShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">Der Typ der Schlüssel.</typeparam>
        <param name="shardMapName">Der Name der shardzuordnung.</param>
        <summary>
            Erstellt eine Liste basierend <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" />.
            </summary>
        <returns>Liste der shardzuordnung mit dem angegebenen Namen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRangeShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt; CreateRangeShardMap&lt;TKey&gt; (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1&lt;!!TKey&gt; CreateRangeShardMap&lt;TKey&gt;(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.CreateRangeShardMap``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRangeShardMap(Of TKey) (shardMapName As String) As RangeShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.CreateRangeShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;'Key&gt;" Usage="shardMapManager.CreateRangeShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">Der Typ der Schlüssel.</typeparam>
        <param name="shardMapName">Der Name der shardzuordnung.</param>
        <summary>
            Erstellen Sie eine bereichsbasierte <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" />.
            </summary>
        <returns>Bereich der shardzuordnung mit dem angegebenen Namen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteShardMap">
      <MemberSignature Language="C#" Value="public void DeleteShardMap (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap shardMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteShardMap(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap shardMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.DeleteShardMap(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap)" />
      <MemberSignature Language="F#" Value="member this.DeleteShardMap : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap -&gt; unit" Usage="shardMapManager.DeleteShardMap shardMap" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMap" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
      </Parameters>
      <Docs>
        <param name="shardMap">Shardmap entfernt werden soll.</param>
        <summary>
            Entfernt die angegebenen shardzuordnung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDistinctShardLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; GetDistinctShardLocations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; GetDistinctShardLocations() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetDistinctShardLocations" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDistinctShardLocations () As IEnumerable(Of ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.GetDistinctShardLocations : unit -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" Usage="shardMapManager.GetDistinctShardLocations " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate", Justification="Method is appropriate here because we're not just returning object state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Speicherorte für unterschiedlichen Shard aus der shardzuordnungs-Manager ab.
            </summary>
        <returns>Die Auflistung der Shard-Speicherorte, die die shardzuordnungs-Manager zugeordnet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetListShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt; GetListShardMap&lt;TKey&gt; (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1&lt;!!TKey&gt; GetListShardMap&lt;TKey&gt;(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetListShardMap``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetListShardMap(Of TKey) (shardMapName As String) As ListShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.GetListShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;'Key&gt;" Usage="shardMapManager.GetListShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">Typ des Schlüssels.</typeparam>
        <param name="shardMapName">Der Name der shardzuordnung.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" /> angegebenem Spaltennamen. 
            </summary>
        <returns>Resultierende ShardMap.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRangeShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt; GetRangeShardMap&lt;TKey&gt; (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1&lt;!!TKey&gt; GetRangeShardMap&lt;TKey&gt;(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetRangeShardMap``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRangeShardMap(Of TKey) (shardMapName As String) As RangeShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.GetRangeShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;'Key&gt;" Usage="shardMapManager.GetRangeShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">Typ des Schlüssels.</typeparam>
        <param name="shardMapName">Der Name der shardzuordnung.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" /> angegebenem Spaltennamen. 
            </summary>
        <returns>Resultierende ShardMap.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRecoveryManager">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager GetRecoveryManager ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager GetRecoveryManager() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetRecoveryManager" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRecoveryManager () As RecoveryManager" />
      <MemberSignature Language="F#" Value="member this.GetRecoveryManager : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager" Usage="shardMapManager.GetRecoveryManager " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate", Justification="Method is appropriate here because we're not just returning object state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft den Wiederherstellungs-Manager für die aktuelle Shard Zuordnung Managerinstanz ab.
            </summary>
        <returns>
            Wiederherstellungs-Manager für die shardzuordnungs-Manager.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaInfoCollection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection GetSchemaInfoCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection GetSchemaInfoCollection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetSchemaInfoCollection" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSchemaInfoCollection () As SchemaInfoCollection" />
      <MemberSignature Language="F#" Value="member this.GetSchemaInfoCollection : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection" Usage="shardMapManager.GetSchemaInfoCollection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate", Justification="Method is appropriate here because we're not just returning object state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft das Schemaobjekt für die Sammlung von Informationen für die aktuelle Shard Zuordnung Managerinstanz ab.
            </summary>
        <returns>Info-schemaauflistung für shardzuordnungs-Manager.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMap">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap GetShardMap (string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap GetShardMap(string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetShardMap(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMap (shardMapName As String) As ShardMap" />
      <MemberSignature Language="F#" Value="member this.GetShardMap : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" Usage="shardMapManager.GetShardMap shardMapName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardMapName">Der Name der shardzuordnung.</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> angegebenem Spaltennamen.
            </summary>
        <returns>Shardmap mit der angegebene Name.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMaps">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&gt; GetShardMaps ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&gt; GetShardMaps() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.GetShardMaps" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMaps () As IEnumerable(Of ShardMap)" />
      <MemberSignature Language="F#" Value="member this.GetShardMaps : unit -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&gt;" Usage="shardMapManager.GetShardMaps " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1024:UsePropertiesWhereAppropriate", Justification="Method is appropriate here because we're not just returning object state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft alle shardzuordnungen der shardzuordnungs-Manager zugeordnet.
            </summary>
        <returns>Die Auflistung von shardzuordnungen der shardzuordnungs-Manager zugeordnet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetListShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public bool TryGetListShardMap&lt;TKey&gt; (string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt; shardMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetListShardMap&lt;TKey&gt;(string shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1&lt;!!TKey&gt;&amp; shardMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.TryGetListShardMap``1(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap{``0}@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetListShardMap(Of TKey) (shardMapName As String, ByRef shardMap As ListShardMap(Of TKey)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetListShardMap : string *  -&gt; bool" Usage="shardMapManager.TryGetListShardMap (shardMapName, shardMap)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="shardMap" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">Typ des Schlüssels.</typeparam>
        <param name="shardMapName">Der Name der shardzuordnung.</param>
        <param name="shardMap">Shardzuordnung mit dem angegebenen Namen.</param>
        <summary>
            Versucht, erhält eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" /> angegebenem Spaltennamen. 
            </summary>
        <returns>
          <c>"true"</c> Wenn shardzuordnung mit dem angegebenen Namen gefunden wurde, <c>"false"</c> andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetRangeShardMap&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public bool TryGetRangeShardMap&lt;TKey&gt; (string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt; shardMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetRangeShardMap&lt;TKey&gt;(string shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1&lt;!!TKey&gt;&amp; shardMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.TryGetRangeShardMap``1(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap{``0}@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetRangeShardMap(Of TKey) (shardMapName As String, ByRef shardMap As RangeShardMap(Of TKey)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetRangeShardMap : string *  -&gt; bool" Usage="shardMapManager.TryGetRangeShardMap (shardMapName, shardMap)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="shardMap" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap&lt;TKey&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">Typ des Schlüssels.</typeparam>
        <param name="shardMapName">Der Name der shardzuordnung.</param>
        <param name="shardMap">Shardzuordnung mit dem angegebenen Namen.</param>
        <summary>
            Versucht, erhält eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.RangeShardMap`1" /> angegebenem Spaltennamen. 
            </summary>
        <returns>
          <c>"true"</c> Wenn shardzuordnung mit dem angegebenen Namen gefunden wurde, <c>"false"</c> andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetShardMap">
      <MemberSignature Language="C#" Value="public bool TryGetShardMap (string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap shardMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetShardMap(string shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&amp; shardMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.TryGetShardMap(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetShardMap (shardMapName As String, ByRef shardMap As ShardMap) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetShardMap : string *  -&gt; bool" Usage="shardMapManager.TryGetShardMap (shardMapName, shardMap)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardMapName" Type="System.String" />
        <Parameter Name="shardMap" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="shardMapName">Der Name der shardzuordnung.</param>
        <param name="shardMap">Shardzuordnung mit dem angegebenen Namen.</param>
        <summary>
            Versucht, erhält eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" /> angegebenem Spaltennamen.
            </summary>
        <returns>
          <c>"true"</c> Wenn shardzuordnung mit dem angegebenen Namen gefunden wurde, <c>"false"</c> andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeGlobalStore">
      <MemberSignature Language="C#" Value="public void UpgradeGlobalStore ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpgradeGlobalStore() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.UpgradeGlobalStore" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpgradeGlobalStore ()" />
      <MemberSignature Language="F#" Value="member this.UpgradeGlobalStore : unit -&gt; unit" Usage="shardMapManager.UpgradeGlobalStore " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Hosting von globalen shardzuordnung auf die neueste Version von der Bibliothek unterstützt Upgrades zu speichern.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeLocalStore">
      <MemberSignature Language="C#" Value="public void UpgradeLocalStore (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpgradeLocalStore(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager.UpgradeLocalStore(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpgradeLocalStore (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.UpgradeLocalStore : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="shardMapManager.UpgradeLocalStore location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location">So aktualisieren Sie Shard-Speicherort.</param>
        <summary>
            Upgrades Speicherort auf die neueste Version von der Bibliothek unterstützt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>