<Type Name="RecoveryManager" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager">
  <TypeSignature Language="C#" Value="public sealed class RecoveryManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RecoveryManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RecoveryManager" />
  <TypeSignature Language="F#" Value="type RecoveryManager = class" />
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
            Verwaltet unterschiedliche Recovery Aufgaben im Zusammenhang mit für eine shardzuordnungs-Manager. Er erleichtert das Auflösen von Probleme mit beschädigten Daten zwischen Shards Zuordnung Informationen lokal gespeichert werden, auf die Shards und in der globalen Shard Map-Manager-Datenbank. Es wird auch mit bestimmten "leider" Recovery-Szenarien, in der Wiederherstellung der shardzuordnungen von datenbanksicherungen oder Datenbankkopien erforderlich ist.
            </summary>
    <remarks>
            Beachten Sie, dass einige der Wiederherstellungsmethoden nicht behebbaren Datenverlust bei nicht ordnungsgemäßer verursachen können. Es wird empfohlen, Sicherungen oder Kopien aller Datenbanken, die in Wiederherstellungsvorgänge einbezogen werden. 
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AttachShard">
      <MemberSignature Language="C#" Value="public void AttachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AttachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.AttachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachShard (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.AttachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="recoveryManager.AttachShard location" />
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
        <param name="location">Der Speicherort des betreffenden Shards angefügt wird.</param>
        <summary>
            Fügt einen Shard an die shardzuordnungs-Manager an. Frühere Versionen von Zuordnungen für die gleiche shardzuordnung werden automatisch aktualisiert werden, wenn neuere Versionen auf den Shard anzufügenden gefunden werden.
            Nach dem Anfügen eines Shards <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> aufgerufen werden, um das Prüfen auf Inkonsistenzen, die manuelle rechtfertigen Auflösung in Konflikt stehen.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachShard">
      <MemberSignature Language="C#" Value="public void AttachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AttachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.AttachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AttachShard (location As ShardLocation, shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.AttachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; unit" Usage="recoveryManager.AttachShard (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1502:AvoidExcessiveComplexity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">Der Speicherort des betreffenden Shards angefügt wird.</param>
        <param name="shardMapName">Optionale Zeichenfolge, die auf den Namen der shardzuordnung filtern.</param>
        <summary>
            Fügt einen Shard an die shardzuordnungs-Manager an. Frühere Versionen von Zuordnungen für die gleiche shardzuordnung werden automatisch aktualisiert werden, wenn neuere Versionen auf den Shard anzufügenden gefunden werden.
            Shard Speicherort wird auf neueste Version des lokalen Speichers im Rahmen dieses Vorgangs aktualisiert werden.
            Nach dem Anfügen eines Shards <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> aufgerufen werden, um das Prüfen auf Inkonsistenzen, die manuelle rechtfertigen Auflösung in Konflikt stehen.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetachShard">
      <MemberSignature Language="C#" Value="public void DetachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DetachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DetachShard (location As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.DetachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; unit" Usage="recoveryManager.DetachShard location" />
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
        <param name="location">Der Speicherort des betreffenden Shards getrennt wird.</param>
        <summary>
            Trennt den angegebenen Shard aus der shardzuordnungs-Manager. Auf den Shard zu löschenden zeigen Mappings werden von dieser Methode automatisch entfernt werden.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetachShard">
      <MemberSignature Language="C#" Value="public void DetachShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DetachShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetachShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DetachShard (location As ShardLocation, shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.DetachShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; unit" Usage="recoveryManager.DetachShard (location, shardMapName)" />
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
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">Der Speicherort des betreffenden Shards getrennt wird.</param>
        <param name="shardMapName">Optionale Zeichenfolge, die auf den Namen der shardzuordnung filtern.</param>
        <summary>
            Trennt den angegebenen Shard aus der shardzuordnungs-Manager. Auf den Shard zu löschenden zeigen Mappings werden von dieser Methode automatisch entfernt werden.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="VB.NET" Value="Public Function DetectMappingDifferences (location As ShardLocation) As IEnumerable(Of RecoveryToken)" />
      <MemberSignature Language="F#" Value="member this.DetectMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" Usage="recoveryManager.DetectMappingDifferences location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort des Shard für das Erkennen von Inkonsistenzen.</param>
        <summary>
            Listet die Unterschiede in den Zuordnungen zwischen der globalen Shard Map-Manager-Datenbank und der lokalen Shard-Datenbank in den angegebenen Shard-Speicherort.
            </summary>
        <returns>Auflistung von Token für die weitere Auflösung Aufgaben verwendet werden soll (siehe <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />).</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetectMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt; DetectMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation location, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DetectMappingDifferences (location As ShardLocation, shardMapName As String) As IEnumerable(Of RecoveryToken)" />
      <MemberSignature Language="F#" Value="member this.DetectMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;" Usage="recoveryManager.DetectMappingDifferences (location, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1506:AvoidExcessiveClassCoupling")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Maintainability", "CA1502:AvoidExcessiveComplexity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort des Shard für das Erkennen von Inkonsistenzen.</param>
        <param name="shardMapName">Optionaler Parameter zum Angeben einer bestimmten shardzuordnung.</param>
        <summary>
            Listet die Unterschiede in den Zuordnungen zwischen der globalen Shard Map-Manager-Datenbank und der lokalen Shard-Datenbank in den angegebenen Shard-Speicherort.
            </summary>
        <returns>Auflistung von Token für die weitere Auflösung Aufgaben verwendet werden soll (siehe <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />).</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingDifferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt; GetMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt; GetMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingDifferences (token As RecoveryToken) As IDictionary(Of ShardRange, MappingLocation)" />
      <MemberSignature Language="F#" Value="member this.GetMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt;" Usage="recoveryManager.GetMappingDifferences token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</param>
        <summary>
            Gibt ein Wörterbuch von Bereichsposition-Schlüssel-Wert-Paaren zurück. Der Speicherort zurückgegeben wird ein Enumerator, der angibt, ob eine bestimmte Bereich-(oder) vorhanden, nur in der lokalen shardzuordnung, nur in der globalen shardzuordnung oder beides handelt. Bereiche, die nicht in einer shardzuordnung enthalten darf keine Unterschiede enthalten, damit diese Bereiche nicht angezeigt werden.
            </summary>
        <returns>Der Satz von Bereichen und ihre entsprechenden <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingLocation" />.</returns>
        <remarks>
            Diese Methode setzt voraus, einen vorherigen Aufruf von <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> , der die Wiederherstellung tokenparameter bereitstellt.
            Das Ergebnis dieser Methode wird üblicherweise in nachfolgende Aufrufe verwendet, um die Inkonsistenzen aufzulösen, wie z. B. <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" /> oder <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />. 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardInfo">
      <MemberSignature Language="C#" Value="public void GetShardInfo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType mapType, out string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetShardInfo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, [out] valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp; mapType, [out] string&amp; shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardInfo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType@,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetShardInfo (token As RecoveryToken, ByRef mapType As ShardMapType, ByRef shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.GetShardInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken *  *  -&gt; unit" Usage="recoveryManager.GetShardInfo (token, mapType, shardMapName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="1#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="mapType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp;" RefType="out" />
        <Parameter Name="shardMapName" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</param>
        <param name="mapType">Der Ausgabetyp Shardmap (Bereichs- oder Listen).</param>
        <param name="shardMapName">Der Ausgabename der shardzuordnung.</param>
        <summary>
            Ruft Shard Map-Typ und Name auf Grundlage von zurückgegebene Token <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardInfo">
      <MemberSignature Language="C#" Value="public void GetShardInfo (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType mapType, out string shardMapName, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetShardInfo(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, [out] valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp; mapType, [out] string&amp; shardMapName, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&amp; shardLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardInfo(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType@,System.String@,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation@)" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetShardInfo (token As RecoveryToken, ByRef mapType As ShardMapType, ByRef shardMapName As String, ByRef shardLocation As ShardLocation)" />
      <MemberSignature Language="F#" Value="member this.GetShardInfo : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken *  *  *  -&gt; unit" Usage="recoveryManager.GetShardInfo (token, mapType, shardMapName, shardLocation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="3#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="1#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="mapType" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType&amp;" RefType="out" />
        <Parameter Name="shardMapName" Type="System.String&amp;" RefType="out" />
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</param>
        <param name="mapType">Ausgaben Shard Map-Typ (Bereichs- oder Listen).</param>
        <param name="shardMapName">Namen der shardzuordnung Ausgaben.</param>
        <param name="shardLocation">Ausgaben Shard-Speicherort</param>
        <summary>
            Ruft Shard Typ, Name und Shard Standorte der Karte basiert auf dem Token Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation GetShardLocation (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation GetShardLocation(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardLocation(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardLocation (token As RecoveryToken) As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.GetShardLocation : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="recoveryManager.GetShardLocation token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token">Wiederherstellungstoken zurückgegeben wird, aus<see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /></param>
        <summary>
            Gibt der Shard-Speicherort, der die lokale shardzuordnung von verarbeiteten <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.
            </summary>
        <returns>Speicherort des betreffenden Shards auf den Satz der Zuordnung der Unterschiede festgestellt werden, entsprechende <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMapName">
      <MemberSignature Language="C#" Value="public string GetShardMapName (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetShardMapName(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardMapName(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMapName (token As RecoveryToken) As String" />
      <MemberSignature Language="F#" Value="member this.GetShardMapName : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; string" Usage="recoveryManager.GetShardMapName token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</param>
        <summary>
            Gibt den shardzuordnungsnamen von der shardzuordnung von verarbeiteten <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.
            </summary>
        <returns>Der Name des der shardzuordnung für das angegebene Recovery-Token.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShardMapType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType GetShardMapType (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType GetShardMapType(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetShardMapType(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShardMapType (token As RecoveryToken) As ShardMapType" />
      <MemberSignature Language="F#" Value="member this.GetShardMapType : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType" Usage="recoveryManager.GetShardMapType token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
      </Parameters>
      <Docs>
        <param name="token">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</param>
        <summary>
            Gibt der Shard-Map-Typ, von der shardzuordnung von verarbeiteten <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.
            </summary>
        <returns>Der Typ des Shard Zuordnung (Liste in Bereich, usw.) entspricht, mit dem Recovery-Token.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShard">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShard (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; ranges);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShard(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; ranges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShard(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShard (token As RecoveryToken, ranges As IEnumerable(Of ShardRange))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShard : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken * seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShard (token, ranges)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="1")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="ranges" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardRange&gt;" />
      </Parameters>
      <Docs>
        <param name="token">Das Recovery-Token von einem vorherigen Aufruf von <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</param>
        <param name="ranges">Der Satz von Bereichen an, um auf den lokalen Shard behalten Sie beim Neuerstellen der lokalen shardzuordnung.</param>
        <summary>
             Erstellt eine shardzuordnung lokalen Bereich aus einer Liste von inkonsistenten Shard Bereiche von erkannten neu <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" /> und Zugriff auf die dann von <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.GetMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken)" />.
             Die resultierende lokalen Bereich shardzuordnung wird immer noch nicht mit der globalen shardzuordnung in den Shard-Map-Manager-Datenbank sein. Ein nachfolgender Aufruf von <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" /> ist erforderlich, um das System wieder in einen fehlerfreien Zustand zu versetzen.
             </summary>
        <remarks>
             Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
             
            Nur Shard Bereichen mit Inkonsistenzen können mit dieser Methode neu erstellt werden. Alle Bereiche mit keine Inkonsistenzen zwischen den lokalen Shard und der globale shardzuordnung werden auf den lokalen Shard unverändert beibehalten werden und werden durch diesen Aufruf nicht betroffen.
             Nachfolgende Änderungen an die nicht in Konflikt stehender Zuordnungen können später mithilfe der regulären Schnittstellen in den shardzuordnungs-Manager vorgenommen werden. Es ist nicht notwendig, den Wiederherstellungs-Manager zu verwenden, nicht in Konflikt stehender Zuordnungen ändern.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardMapManagerFromShards">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardMapManagerFromShards (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardMapManagerFromShards(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardMapManagerFromShards(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardMapManagerFromShards (shardLocations As IEnumerable(Of ShardLocation))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardMapManagerFromShards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardMapManagerFromShards shardLocations" />
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
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
      </Parameters>
      <Docs>
        <param name="shardLocations">Die Auflistung der Shard-Positionen.</param>
        <summary>
            Rekonstruiert eine angegebene eine Sammlung von Shard-Speicherorte die shardzuordnungs-Manager basierend auf Informationen über die Zuordnung in den einzelnen Shards gespeichert. Die angegebene Shards müssen bereits in der globalen shardzuordnung registriert werden. Diese Methode wird nur Zuordnungen neu erstellt. Es wird nicht Shard Mitgliedschaft in der globalen shardzuordnung neu erstellt.
            Wenn die Informationen in den einzelnen shardzuordnungen oder inkonsistent, ist das Verhalten nicht definiert.
            Keine Sperren Cross Shard vorgenommen werden sind, wenn während der Ausführung dieser Methode alle Shards inkonsistent werden, der finalen Status der globalen shardzuordnung möglicherweise beschädigt.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardMapManagerFromShards">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardMapManagerFromShards (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardMapManagerFromShards(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardMapManagerFromShards(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardMapManagerFromShards (shardLocations As IEnumerable(Of ShardLocation), shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardMapManagerFromShards : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardMapManagerFromShards (shardLocations, shardMapName)" />
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
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations">Die Auflistung der Shard-Positionen.</param>
        <param name="shardMapName">Optionaler Name des shardzuordnung. Wenn nicht angegeben, wird versucht, die Wiederherstellung alle shardzuordnungen für jeden Shard vorhanden.</param>
        <summary>
            Rekonstruiert eine angegebene eine Sammlung von Shard-Speicherorte die shardzuordnungs-Manager basierend auf Informationen über die Zuordnung in den einzelnen Shards gespeichert. Die angegebene Shards müssen bereits in der globalen shardzuordnung registriert werden. Diese Methode wird nur Zuordnungen neu erstellt. Es wird nicht Shard Mitgliedschaft in der globalen shardzuordnung neu erstellt.
            Wenn die Informationen in den einzelnen shardzuordnungen oder inkonsistent, ist das Verhalten nicht definiert.
            Keine Sperren Cross Shard vorgenommen werden sind, wenn während der Ausführung dieser Methode alle Shards inkonsistent werden, der finalen Status der globalen shardzuordnung möglicherweise beschädigt.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardsFromShardMapManager">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardsFromShardMapManager (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardsFromShardMapManager(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardsFromShardMapManager(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardsFromShardMapManager (shardLocations As IEnumerable(Of ShardLocation))" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardsFromShardMapManager : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardsFromShardMapManager shardLocations" />
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
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
      </Parameters>
      <Docs>
        <param name="shardLocations">Die Auflistung der Shard-Positionen.</param>
        <summary>
            Erhält eine Auflistung von Shard-Speicherorte, Basis rekonstruiert, ordnet lokalen shard, auf der gespeicherten Zuordnungsinformationen in der globalen shardzuordnung. Die angegebene Shards müssen bereits in der globalen shardzuordnung registriert werden. Diese Methode wird nur Zuordnungen neu erstellt. Es wird nicht Shard Mitgliedschaft in der globalen shardzuordnung neu erstellt.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebuildMappingsOnShardsFromShardMapManager">
      <MemberSignature Language="C#" Value="public void RebuildMappingsOnShardsFromShardMapManager (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RebuildMappingsOnShardsFromShardMapManager(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; shardLocations, string shardMapName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.RebuildMappingsOnShardsFromShardMapManager(System.Collections.Generic.IEnumerable{Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RebuildMappingsOnShardsFromShardMapManager (shardLocations As IEnumerable(Of ShardLocation), shardMapName As String)" />
      <MemberSignature Language="F#" Value="member this.RebuildMappingsOnShardsFromShardMapManager : seq&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt; * string -&gt; unit" Usage="recoveryManager.RebuildMappingsOnShardsFromShardMapManager (shardLocations, shardMapName)" />
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
        <Parameter Name="shardLocations" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation&gt;" />
        <Parameter Name="shardMapName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocations">Die Auflistung der Shard-Positionen.</param>
        <param name="shardMapName">Optionaler Parameter, um nach den Namen der shardzuordnung zu filtern. Wenn nicht angegeben, werden alle shardzuordnungen neu erstellt werden.</param>
        <summary>
            Erhält eine Auflistung von Shard-Speicherorte, Basis rekonstruiert, ordnet lokalen shard, auf der gespeicherten Zuordnungsinformationen in der globalen shardzuordnung. Die angegebene Shards müssen bereits in der globalen shardzuordnung registriert werden. Diese Methode wird nur Zuordnungen neu erstellt. Es wird nicht Shard Mitgliedschaft in der globalen shardzuordnung neu erstellt.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveMappingDifferences">
      <MemberSignature Language="C#" Value="public void ResolveMappingDifferences (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution resolution);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResolveMappingDifferences(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken token, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution resolution) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.ResolveMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResolveMappingDifferences (token As RecoveryToken, resolution As MappingDifferenceResolution)" />
      <MemberSignature Language="F#" Value="member this.ResolveMappingDifferences : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution -&gt; unit" Usage="recoveryManager.ResolveMappingDifferences (token, resolution)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryToken" />
        <Parameter Name="resolution" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.MappingDifferenceResolution" />
      </Parameters>
      <Docs>
        <param name="token">Wiederherstellungstoken Merry <see cref="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Recovery.RecoveryManager.DetectMappingDifferences(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />.</param>
        <param name="resolution">Die Auflösungsstrategie für die Auflösung verwendet werden.</param>
        <summary>
            Wählt einen von der shardzuordnungen (lokal oder global) als Quelle für Wahrheit aus, und schaltet Zuordnungen auf beide synchron shardzuordnungen.
            </summary>
        <remarks>
            Beachten Sie, dass diese Methode nicht behebbaren Datenverlust führen kann. Stellen Sie sicher, dass Sie Sicherungen oder Kopien Ihrer Datenbanken erstellt haben, und nur mit großer Umsicht fortfahren.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>