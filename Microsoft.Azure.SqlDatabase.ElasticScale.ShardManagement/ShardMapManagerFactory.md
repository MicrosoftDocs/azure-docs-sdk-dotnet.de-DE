<Type Name="ShardMapManagerFactory" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory">
  <TypeSignature Language="C#" Value="public static class ShardMapManagerFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ShardMapManagerFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class ShardMapManagerFactory" />
  <TypeSignature Language="F#" Value="type ShardMapManagerFactory = class" />
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
            Factory für <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" />s erleichtert die Erstellung und Verwaltung von Shard Zuordnung Manager persistenten Status. Verwenden Sie diese Klasse als Eintrag zeigen Sie auf die Bibliothek-Objekthierarchie.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreatePerformanceCategoryAndCounters">
      <MemberSignature Language="C#" Value="public static void CreatePerformanceCategoryAndCounters ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreatePerformanceCategoryAndCounters() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreatePerformanceCategoryAndCounters" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub CreatePerformanceCategoryAndCounters ()" />
      <MemberSignature Language="F#" Value="static member CreatePerformanceCategoryAndCounters : unit -&gt; unit" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreatePerformanceCategoryAndCounters " />
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
            Erstellen von Shard Management Leistungsindikatorkategorie und Leistungsindikatoren
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSqlShardMapManager (connectionString As String) As ShardMapManager" />
      <MemberSignature Language="F#" Value="static member CreateSqlShardMapManager : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager connectionString" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die Verbindungsparameter für die Erstellung von Shard-Schema-Manager-Datenbank verwendet.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> und entsprechende Speicher Strukturen in der angegebenen SQL Server-Datenbank mit <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.KeepExisting" /> und <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />.
            </summary>
        <returns>
            Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager(string connectionString, class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior)" />
      <MemberSignature Language="F#" Value="static member CreateSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager (connectionString, retryBehavior)" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="retryBehavior" Type="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die Verbindungsparameter für die Erstellung von Shard-Schema-Manager-Datenbank verwendet.</param>
        <param name="retryBehavior">Verhalten für die vorübergehende Ausnahmen, die in den Speicher zu erkennen.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> und entsprechende Speicher Strukturen in der angegebenen SQL Server-Datenbank mit <see cref="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode.KeepExisting" />.
            </summary>
        <returns>
            Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode createMode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode createMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSqlShardMapManager (connectionString As String, createMode As ShardMapManagerCreateMode) As ShardMapManager" />
      <MemberSignature Language="F#" Value="static member CreateSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager (connectionString, createMode)" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="createMode" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die Verbindungsparameter für die Erstellung von Shard-Schema-Manager-Datenbank verwendet.</param>
        <param name="createMode">Beschreibt die Option zum Erstellen von Shard-Schema-Manager-Datenbank vom Benutzer ausgewählt.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> und entsprechende Speicher Strukturen in der angegebenen SQL Server-Datenbank mit <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />.
            </summary>
        <returns>
            Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode createMode, Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager CreateSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode createMode, class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode,Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior)" />
      <MemberSignature Language="F#" Value="static member CreateSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode * Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.CreateSqlShardMapManager (connectionString, createMode, retryBehavior)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="2")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Reliability", "CA2000:Dispose objects before losing scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="createMode" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerCreateMode" />
        <Parameter Name="retryBehavior" Type="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die Verbindungsparameter für die Erstellung von Shard-Schema-Manager-Datenbank verwendet.</param>
        <param name="createMode">Beschreibt die Option zum Erstellen von Shard-Schema-Manager-Datenbank vom Benutzer ausgewählt.</param>
        <param name="retryBehavior">Verhalten für die vorübergehende Ausnahmen, die in den Speicher zu erkennen.</param>
        <summary>
            Erstellt eine <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> und entsprechende Speicher Strukturen, in der angegebenen SQL Server-Datenbank.
            </summary>
        <returns>
            Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager GetSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager GetSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.GetSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetSqlShardMapManager (connectionString As String, loadPolicy As ShardMapManagerLoadPolicy) As ShardMapManager" />
      <MemberSignature Language="F#" Value="static member GetSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.GetSqlShardMapManager (connectionString, loadPolicy)" />
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
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="loadPolicy" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verwendet zum Ausführen von Vorgängen für Shard Verbindungsparameter zuordnen Manager-Datenbanken.</param>
        <param name="loadPolicy">Richtlinie für die Initialisierung.</param>
        <summary>
            Ruft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> von beibehalten Status in einer SQL Server-Datenbank mit <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" />. 
            </summary>
        <returns>
            Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager GetSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager GetSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.GetSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy,Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior)" />
      <MemberSignature Language="F#" Value="static member GetSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy * Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.GetSqlShardMapManager (connectionString, loadPolicy, retryBehavior)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="loadPolicy" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
        <Parameter Name="retryBehavior" Type="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verwendet zum Ausführen von Vorgängen für Shard Verbindungsparameter zuordnen Manager-Datenbanken.</param>
        <param name="loadPolicy">Richtlinie für die Initialisierung.</param>
        <param name="retryBehavior">Verhalten für die vorübergehende Ausnahmen, die in den Speicher zu erkennen.</param>
        <summary>
            Ruft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> von beibehaltenen Zustand in einer SQL Server-Datenbank.
            </summary>
        <returns>
            Ein Shard Map-Objekt-Manager zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static bool TryGetSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager shardMapManager);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryGetSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager&amp; shardMapManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.TryGetSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryGetSqlShardMapManager (connectionString As String, loadPolicy As ShardMapManagerLoadPolicy, ByRef shardMapManager As ShardMapManager) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryGetSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy *  -&gt; bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.TryGetSqlShardMapManager (connectionString, loadPolicy, shardMapManager)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="loadPolicy" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
        <Parameter Name="shardMapManager" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verwendet zum Ausführen von Vorgängen für Shard Verbindungsparameter zuordnen Manager-Datenbanken.</param>
        <param name="loadPolicy">Richtlinie für die Initialisierung.</param>
        <param name="shardMapManager">Shard Map-Manager-Objekt zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen oder <c>null</c> für den Fall, dass shardzuordnungs-Manager nicht vorhanden ist.</param>
        <summary>
            Ruft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> von beibehaltenen Zustand in einer SQL Server-Datenbank.
            </summary>
        <returns>
          <c>"true"</c> Wenn einem Shard Map-Manager-Objekt erstellt wurde, <c>"false"</c> andernfalls.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetSqlShardMapManager">
      <MemberSignature Language="C#" Value="public static bool TryGetSqlShardMapManager (string connectionString, Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior, out Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager shardMapManager);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryGetSqlShardMapManager(string connectionString, valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy loadPolicy, class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior retryBehavior, [out] class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager&amp; shardMapManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.TryGetSqlShardMapManager(System.String,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy,Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior,Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager@)" />
      <MemberSignature Language="F#" Value="static member TryGetSqlShardMapManager : string * Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy * Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior *  -&gt; bool" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerFactory.TryGetSqlShardMapManager (connectionString, loadPolicy, retryBehavior, shardMapManager)" />
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
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", MessageId="2#")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="loadPolicy" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManagerLoadPolicy" />
        <Parameter Name="retryBehavior" Type="Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior" />
        <Parameter Name="shardMapManager" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verwendet zum Ausführen von Vorgängen für Shard Verbindungsparameter zuordnen Manager-Datenbanken.</param>
        <param name="loadPolicy">Richtlinie für die Initialisierung.</param>
        <param name="retryBehavior">Verhalten für die vorübergehende Ausnahmen, die in den Speicher zu erkennen.</param>
        <param name="shardMapManager">Shard Map-Manager-Objekt zum Ausführen von Management verwendet und Lesevorgänge für shardzuordnungen, Shards und Shard-Zuordnungen oder <c>null</c> für den Fall, dass shardzuordnungs-Manager nicht vorhanden ist.</param>
        <summary>
            Ruft <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> von beibehaltenen Zustand in einer SQL Server-Datenbank.
            </summary>
        <returns>
          <c>"true"</c> Wenn einem Shard Map-Manager-Objekt erstellt wurde, <c>"false"</c> andernfalls.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>