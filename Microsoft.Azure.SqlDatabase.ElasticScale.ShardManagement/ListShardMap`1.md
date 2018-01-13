<Type Name="ListShardMap&lt;TKey&gt;" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;">
  <TypeSignature Language="C#" Value="public sealed class ListShardMap&lt;TKey&gt; : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListShardMap`1&lt;TKey&gt; extends Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListShardMap(Of TKey)&#xA;Inherits ShardMap" />
  <TypeSignature Language="F#" Value="type ListShardMap&lt;'Key&gt; = class&#xA;    inherit ShardMap&#xA;    interface ICloneable&lt;ShardMap&gt;&#xA;    interface ICloneable&lt;ListShardMap&lt;'Key&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TKey">Typ des Schlüssels.</typeparam>
    <summary>
            Stellt eine shardzuordnung von Punkten, wo mit dem angegebenen Schlüssel sind.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt; Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1&lt;!TKey&gt; Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As ListShardMap(Of TKey)" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;'Key&gt;&#xA;override this.Clone : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;'Key&gt;" Usage="listShardMap.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ICloneable`1.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Klont die shardzuordnung angegebenen Liste.
            </summary>
        <returns>Eine geklonte Instanz der shardzuordnung Liste.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneCore">
      <MemberSignature Language="C#" Value="protected override Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap CloneCore ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap CloneCore() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.CloneCore" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CloneCore () As ShardMap" />
      <MemberSignature Language="F#" Value="override this.CloneCore : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap" Usage="listShardMap.CloneCore " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMap</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Klont die aktuelle Instanz der Shard-Zuordnung.
            </summary>
        <returns>Geklonte Shard Zuordnungsinstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePointMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; CreatePointMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;TKey&gt; creationInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; CreatePointMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo`1&lt;!TKey&gt; creationInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.CreatePointMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePointMapping (creationInfo As PointMappingCreationInfo(Of TKey)) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.CreatePointMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.CreatePointMapping creationInfo" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creationInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingCreationInfo&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="creationInfo">Informationen zur Zuordnung hinzugefügt werden.</param>
        <summary>
            Erstellt, und fügt eine Punkt-Zuordnung ShardMap hinzu.
            </summary>
        <returns>Neu erstellte Zuordnung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePointMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; CreatePointMapping (TKey point, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; CreatePointMapping(!TKey point, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.CreatePointMapping(`0,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.CreatePointMapping : 'Key * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.CreatePointMapping (point, shard)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="point" Type="TKey" />
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="point">Zeigen Sie für die die Zuordnung erstellt.</param>
        <param name="shard">Shard die Punkt-Zuordnung zugeordnet.</param>
        <summary>
            Erstellt, und fügt eine Punkt-Zuordnung ShardMap hinzu.
            </summary>
        <returns>Neu erstellte Zuordnung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMapping">
      <MemberSignature Language="C#" Value="public void DeleteMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.DeleteMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteMapping (mapping As PointMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.DeleteMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; -&gt; unit" Usage="listShardMap.DeleteMapping mapping" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">Die Zuordnung entfernt wird.</param>
        <summary>
            Entfernt eine Punkt-Zuordnung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingForKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; GetMappingForKey (TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; GetMappingForKey(!TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappingForKey(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingForKey (key As TKey) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.GetMappingForKey : 'Key -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.GetMappingForKey key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="key">Eingabe Schlüsselwert.</param>
        <summary>
            Sucht den Schlüsselwert, und gibt die entsprechende Zuordnung zurück.
            </summary>
        <returns>Zuordnung, enthält die Schlüssel-Wert.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappingLockOwner">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken GetMappingLockOwner (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken GetMappingLockOwner(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappingLockOwner(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappingLockOwner (mapping As PointMapping(Of TKey)) As MappingLockToken" />
      <MemberSignature Language="F#" Value="member this.GetMappingLockOwner : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" Usage="listShardMap.GetMappingLockOwner mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">Eingabebereich-Zuordnung.</param>
        <summary>
            Ruft die Sperre Besitzer-Id, der die angegebene Zuordnung ab.
            </summary>
        <returns>Eine Instanz von <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt; GetMappings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&gt; GetMappings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappings () As IReadOnlyList(Of PointMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.GetMappings : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&gt;" Usage="listShardMap.GetMappings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft alle zeigen Mappings für die shardzuordnung ab.
            </summary>
        <returns>Schreibgeschützte Auflistung von alle zeigen Mappings für die shardzuordnung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; range);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; range) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMappings (range As Range(Of TKey)) As IReadOnlyList(Of PointMapping(Of TKey))" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&gt;" Usage="listShardMap.GetMappings range" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="range" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="range">Punktwert, der eine beliebige Zuordnung mit dem Bereich überlappen, werden zurückgegeben.</param>
        <summary>
            Ruft alle Zuordnungen, die im angegebenen Bereich vorhanden sind.
            </summary>
        <returns>Schreibgeschützte Auflistung der Zuordnungen, die den angegebenen Bereich Einschränkung erfüllen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&gt;" Usage="listShardMap.GetMappings shard" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="shard">Shard für die die Zuordnungen zurückgegeben werden.</param>
        <summary>
            Ruft alle Zuordnungen, die vorhanden sind für den angegebenen Shard ab.
            </summary>
        <returns>Schreibgeschützte Auflistung der Zuordnungen, die die angegebenen Shard Einschränkung erfüllen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt; GetMappings (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt; range, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&gt; GetMappings(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range`1&lt;!TKey&gt; range, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard shard) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.GetMappings(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard)" />
      <MemberSignature Language="F#" Value="member this.GetMappings : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;&gt;" Usage="listShardMap.GetMappings (range, shard)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="1")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Necessary to allow different types of keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="range" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Range&lt;TKey&gt;" />
        <Parameter Name="shard" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Shard" />
      </Parameters>
      <Docs>
        <param name="range">Punktwert, der eine beliebige Zuordnung mit dem Bereich überlappen, werden zurückgegeben.</param>
        <param name="shard">Shard für die die Zuordnungen zurückgegeben werden.</param>
        <summary>
            Ruft alle Zuordnungen, die zwischen existieren aufgrund Bandbreite und Shard erhält.
            </summary>
        <returns>Schreibgeschützte Auflistung der Zuordnungen, die die angegebenen Bereich und Shard Einschränkungen erfüllen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockMapping">
      <MemberSignature Language="C#" Value="public void LockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void LockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.LockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.LockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="listShardMap.LockMapping (mapping, mappingLockToken)" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mapping">Eingabebereich-Zuordnung.</param>
        <param name="mappingLockToken">Eine Instanz von <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />.</param>
        <summary>
            Sperrt die Zuordnung für den angegebenen Besitzer an, den der Zustand einer gesperrten Zuordnung nur von der Sperrenbesitzer geändert werden kann.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarkMappingOffline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; MarkMappingOffline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; MarkMappingOffline(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.MarkMappingOffline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function MarkMappingOffline (mapping As PointMapping(Of TKey)) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.MarkMappingOffline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.MarkMappingOffline mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">Zuordnung von Eingabe Punkt.</param>
        <summary>
            Markiert die angegebene Zuordnung offline.
            </summary>
        <returns>Eine offline-Zuordnung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MarkMappingOnline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; MarkMappingOnline (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; MarkMappingOnline(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.MarkMappingOnline(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function MarkMappingOnline (mapping As PointMapping(Of TKey)) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.MarkMappingOnline : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.MarkMappingOnline mapping" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
      </Parameters>
      <Docs>
        <param name="mapping">Zuordnung von Eingabe Punkt.</param>
        <summary>
            Markiert die angegebene Zuordnung online.
            </summary>
        <returns>Ein online-Zuordnung.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKey">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnectionForKey (TKey key, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnectionForKey(!TKey key, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.OpenConnectionForKey(`0,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKey (key As TKey, connectionString As String) As SqlConnection" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKey : 'Key * string -&gt; System.Data.SqlClient.SqlConnection" Usage="listShardMap.OpenConnectionForKey (key, connectionString)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1061:DoNotHideBaseClassMethods")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Eingabe Schlüsselwert.</param>
        <param name="connectionString">
            Verbindungszeichenfolge mit Anmeldeinformationen, z. B. SQL Server-Anmeldeinformationen oder die integrierte Sicherheit von Einstellungen. Der Hostname des Servers und den Datenbanknamen für den Shard werden von der Suchvorgang für Schlüssel abgerufen.
            </param>
        <summary>
            Öffnet eine reguläre <see cref="T:System.Data.SqlClient.SqlConnection" /> zum Shard, dem der angegebene Schlüssel-Wert zugeordnet ist, mit <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />.
            </summary>
        <returns>Eine geöffnete SqlConnection.</returns>
        <remarks>
            Beachten Sie, dass die <see cref="T:System.Data.SqlClient.SqlConnection" /> durch diesen Aufruf zurückgegebene Objekt ist nicht geschützt gegen vorübergehende Fehler. Aufrufer sollten bewährte Methoden, um die Verbindung für vorübergehende Fehler in ihrem Anwendungscode, z. B. zu schützen, mithilfe der Funktionalität in der Enterprise-Bibliothek von Microsoft Patterns and Practices-Team behandeln vorübergehenden Fehlers folgen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKey">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlConnection OpenConnectionForKey (TKey key, string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.SqlClient.SqlConnection OpenConnectionForKey(!TKey key, string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.OpenConnectionForKey(`0,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKey (key As TKey, connectionString As String, options As ConnectionOptions) As SqlConnection" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKey : 'Key * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Data.SqlClient.SqlConnection" Usage="listShardMap.OpenConnectionForKey (key, connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1061:DoNotHideBaseClassMethods")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <param name="key">Eingabe Schlüsselwert.</param>
        <param name="connectionString">
            Verbindungszeichenfolge mit Anmeldeinformationen, z. B. SQL Server-Anmeldeinformationen oder die integrierte Sicherheit von Einstellungen. Der Hostname des Servers und den Datenbanknamen für den Shard werden von der Suchvorgang für Schlüssel abgerufen.
            </param>
        <param name="options">Optionen für Validierungsvorgänge auf geöffnete Verbindung ausführen.</param>
        <summary>
            Öffnet eine reguläre <see cref="T:System.Data.SqlClient.SqlConnection" /> zum Shard, dem der angegebene Schlüssel-Wert zugeordnet ist.
            </summary>
        <returns>Eine geöffnete SqlConnection.</returns>
        <remarks>
            Beachten Sie, dass die <see cref="T:System.Data.SqlClient.SqlConnection" /> durch diesen Aufruf zurückgegebene Objekt ist nicht geschützt gegen vorübergehende Fehler. Aufrufer sollten bewährte Methoden, um die Verbindung für vorübergehende Fehler in ihrem Anwendungscode, z. B. zu schützen, mithilfe der Funktionalität in der Enterprise-Bibliothek von Microsoft Patterns and Practices-Team behandeln vorübergehenden Fehlers folgen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync (TKey key, string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync(!TKey key, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.OpenConnectionForKeyAsync(`0,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKeyAsync (key As TKey, connectionString As String) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKeyAsync : 'Key * string -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="listShardMap.OpenConnectionForKeyAsync (key, connectionString)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1061:DoNotHideBaseClassMethods")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Eingabe Schlüsselwert.</param>
        <param name="connectionString">
            Verbindungszeichenfolge mit Anmeldeinformationen, z. B. SQL Server-Anmeldeinformationen oder die integrierte Sicherheit von Einstellungen. Der Hostname des Servers und den Datenbanknamen für den Shard werden von der Suchvorgang für Schlüssel abgerufen.
            </param>
        <summary>
            Asynchron öffnet eine reguläre <see cref="T:System.Data.SqlClient.SqlConnection" /> zum Shard, dem der angegebene Schlüssel-Wert zugeordnet ist, mit <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />.
            </summary>
        <returns>Eine Aufgabe, die einer offenen SqlConnection als Ergebnis kapseln</returns>
        <remarks>
            Beachten Sie, dass die <see cref="T:System.Data.SqlClient.SqlConnection" /> durch diesen Aufruf zurückgegebene Objekt ist nicht geschützt gegen vorübergehende Fehler. Aufrufer sollten bewährte Methoden, um die Verbindung für vorübergehende Fehler in ihrem Anwendungscode, z. B. zu schützen, mithilfe der Funktionalität in der Enterprise-Bibliothek von Microsoft Patterns and Practices-Team behandeln vorübergehenden Fehlers folgen.
            Alle nicht-Usage-Fehler im Zusammenhang mit Ausnahmen, die über die zurückgegebene Aufgabe gemeldet werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenConnectionForKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync (TKey key, string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.SqlClient.SqlConnection&gt; OpenConnectionForKeyAsync(!TKey key, string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.OpenConnectionForKeyAsync(`0,System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenConnectionForKeyAsync (key As TKey, connectionString As String, options As ConnectionOptions) As Task(Of SqlConnection)" />
      <MemberSignature Language="F#" Value="override this.OpenConnectionForKeyAsync : 'Key * string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;" Usage="listShardMap.OpenConnectionForKeyAsync (key, connectionString, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1061:DoNotHideBaseClassMethods")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.SqlClient.SqlConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
      </Parameters>
      <Docs>
        <param name="key">Eingabe Schlüsselwert.</param>
        <param name="connectionString">
            Verbindungszeichenfolge mit Anmeldeinformationen, z. B. SQL Server-Anmeldeinformationen oder die integrierte Sicherheit von Einstellungen. Der Hostname des Servers und den Datenbanknamen für den Shard werden von der Suchvorgang für Schlüssel abgerufen.
            </param>
        <param name="options">Optionen für Validierungsvorgänge auf geöffnete Verbindung ausführen.</param>
        <summary>
            Asynchron öffnet eine reguläre <see cref="T:System.Data.SqlClient.SqlConnection" /> zum Shard, dem der angegebene Schlüssel-Wert zugeordnet ist.
            </summary>
        <returns>Eine Aufgabe, die eine geöffnete SqlConnection kapseln.</returns>
        <remarks>
            Beachten Sie, dass die <see cref="T:System.Data.SqlClient.SqlConnection" /> durch diesen Aufruf zurückgegebene Objekt ist nicht geschützt gegen vorübergehende Fehler. Aufrufer sollten bewährte Methoden, um die Verbindung für vorübergehende Fehler in ihrem Anwendungscode, z. B. zu schützen, mithilfe der Funktionalität in der Enterprise-Bibliothek von Microsoft Patterns and Practices-Team behandeln vorübergehenden Fehlers folgen.
            Alle nicht-Usage-Fehler im Zusammenhang mit Ausnahmen, die über die zurückgegebene Aufgabe gemeldet werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetMappingForKey">
      <MemberSignature Language="C#" Value="public bool TryGetMappingForKey (TKey key, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; pointMapping);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetMappingForKey(!TKey key, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt;&amp; pointMapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.TryGetMappingForKey(`0,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0}@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetMappingForKey (key As TKey, ByRef pointMapping As PointMapping(Of TKey)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetMappingForKey : 'Key *  -&gt; bool" Usage="listShardMap.TryGetMappingForKey (key, pointMapping)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="pointMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="key">Eingabe Schlüsselwert.</param>
        <param name="pointMapping">Zuordnung, enthält die Schlüssel-Wert.</param>
        <summary>
            Versucht, sucht der Schlüssel-Wert, und platzieren Sie die entsprechende Zuordnung im <paramref name="pointMapping" />.
            </summary>
        <returns>
          <c>"true"</c> Zuordnung gefunden, <c>"false"</c> andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnlockMapping">
      <MemberSignature Language="C#" Value="public void UnlockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnlockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.UnlockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UnlockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="listShardMap.UnlockMapping mappingLockToken" />
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
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mappingLockToken">Eine Instanz von <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />.</param>
        <summary>
            Entsperrt alle Zuordnungen in dieser Karte, die zu gehören die angegebenen<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnlockMapping">
      <MemberSignature Language="C#" Value="public void UnlockMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; mapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnlockMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; mapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.UnlockMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UnlockMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; unit" Usage="listShardMap.UnlockMapping (mapping, mappingLockToken)" />
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
        <Parameter Name="mapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="mapping">Eingabebereich-Zuordnung.</param>
        <param name="mappingLockToken">Eine Instanz von <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />.</param>
        <summary>
            Die angegebene Zuordnung entsperrt
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; UpdateMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; currentMapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate update);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; UpdateMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; currentMapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate update) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.UpdateMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateMapping (currentMapping As PointMapping(Of TKey), update As PointMappingUpdate) As PointMapping(Of TKey)" />
      <MemberSignature Language="F#" Value="member this.UpdateMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.UpdateMapping (currentMapping, update)" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
        <Parameter Name="update" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate" />
      </Parameters>
      <Docs>
        <param name="currentMapping">Die Zuordnung aktualisiert wird.</param>
        <param name="update">Aktualisierte Eigenschaften der Zuordnung.</param>
        <summary>
            Updates einer <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1" /> mit den Updates, die gemäß der <paramref name="update" /> Parameter.
            </summary>
        <returns>Neue Instanz der Zuordnung mit aktualisierten Informationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMapping">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; UpdateMapping (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt; currentMapping, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate update, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; UpdateMapping(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping`1&lt;!TKey&gt; currentMapping, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate update, class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken mappingLockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ListShardMap`1.UpdateMapping(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping{`0},Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateMapping : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt; * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;'Key&gt;" Usage="listShardMap.UpdateMapping (currentMapping, update, mappingLockToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentMapping" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMapping&lt;TKey&gt;" />
        <Parameter Name="update" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.PointMappingUpdate" />
        <Parameter Name="mappingLockToken" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />
      </Parameters>
      <Docs>
        <param name="currentMapping">Die Zuordnung aktualisiert wird.</param>
        <param name="update">Aktualisierte Eigenschaften des betreffenden Shards.</param>
        <param name="mappingLockToken">Eine Instanz von <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.MappingLockToken" />.</param>
        <summary>
            Aktualisiert eine Punkt-Zuordnung mit den Änderungen, die gemäß der <paramref name="update" /> Parameter.
            </summary>
        <returns>Neue Instanz der Zuordnung mit aktualisierten Informationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>