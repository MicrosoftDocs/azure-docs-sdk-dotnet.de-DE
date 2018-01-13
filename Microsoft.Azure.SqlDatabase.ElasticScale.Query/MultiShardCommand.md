<Type Name="MultiShardCommand" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand">
  <TypeSignature Language="C#" Value="public sealed class MultiShardCommand : System.Data.Common.DbCommand" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MultiShardCommand extends System.Data.Common.DbCommand" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MultiShardCommand&#xA;Inherits DbCommand" />
  <TypeSignature Language="F#" Value="type MultiShardCommand = class&#xA;    inherit DbCommand" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Data.Common.DbCommand</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.DesignerCategory("Code")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ergänzt die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> mit ein Command-Objekt ähnelt der Triade von <see cref="T:System.Data.SqlClient.SqlConnection" />, <see cref="T:System.Data.SqlClient.SqlCommand" />, und <see cref="T:System.Data.SqlClient.SqlDataReader" />. Die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> T-SQL-Command-Anweisung als Eingabe akzeptiert und führt den Befehl über die Auflistung von Shards, die gemäß dem entsprechenden <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" />.
            Die Ergebnisse der Verarbeitung der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> werden über die Execute-Methoden zur Verfügung gestellt und die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public override void Cancel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Cancel() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Cancel" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Cancel ()" />
      <MemberSignature Language="F#" Value="override this.Cancel : unit -&gt; unit" Usage="multiShardCommand.Cancel " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1031:DoNotCatchGeneralExceptionTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Versucht, eine laufende abzubrechen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> und alle derzeit ausgeführte Arbeit, die auf die Shards für den Befehl ausgeführt wird. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandText">
      <MemberSignature Language="C#" Value="public override string CommandText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandText" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property CommandText As String" />
      <MemberSignature Language="F#" Value="member this.CommandText : string with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Security", "CA2100:Review SQL queries for security vulnerabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Befehlstext zum dar, die den Satz von Shards ausgeführt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandTimeout">
      <MemberSignature Language="C#" Value="public override int CommandTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CommandTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property CommandTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.CommandTimeout : int with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Zeit in Sekunden warten, bis der Befehl auf alle Shards ausgeführt werden.
            Der Wert 0 gibt an, zeitlich unbegrenzt warten. Der Standardwert ist 300 Sekunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandTimeoutPerShard">
      <MemberSignature Language="C#" Value="public int CommandTimeoutPerShard { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CommandTimeoutPerShard" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeoutPerShard" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandTimeoutPerShard As Integer" />
      <MemberSignature Language="F#" Value="member this.CommandTimeoutPerShard : int with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeoutPerShard" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Eigenschaft steuert das Zeitlimit für die Ausführung eines Befehls für einzelne Shards.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandType">
      <MemberSignature Language="C#" Value="public override System.Data.CommandType CommandType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Data.CommandType CommandType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property CommandType As CommandType" />
      <MemberSignature Language="F#" Value="member this.CommandType : System.Data.CommandType with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.CommandType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandType" />des auszuführenden Befehls.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection Connection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection Connection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Connection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Connection As MultiShardConnection" />
      <MemberSignature Language="F#" Value="member this.Connection : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Connection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die aktuelle Instanz von der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> mit diesem Befehl verbunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDbParameter">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbParameter CreateDbParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Data.Common.DbParameter CreateDbParameter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CreateDbParameter" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDbParameter () As DbParameter" />
      <MemberSignature Language="F#" Value="override this.CreateDbParameter : unit -&gt; System.Data.Common.DbParameter" Usage="multiShardCommand.CreateDbParameter " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbParameter</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Instanz der DbParameter
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateParameter">
      <MemberSignature Language="C#" Value="public static System.Data.SqlClient.SqlParameter CreateParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Data.SqlClient.SqlParameter CreateParameter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CreateParameter" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateParameter () As SqlParameter" />
      <MemberSignature Language="F#" Value="static member CreateParameter : unit -&gt; System.Data.SqlClient.SqlParameter" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CreateParameter " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlParameter</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine neue Instanz eines <see cref="T:System.Data.SqlClient.SqlParameter" />-Objekts.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DbConnection">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbConnection DbConnection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.Common.DbConnection DbConnection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbConnection" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Property DbConnection As DbConnection" />
      <MemberSignature Language="F#" Value="member this.DbConnection : System.Data.Common.DbConnection with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbConnection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbConnection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Verbindungen mit Shards. Nicht unterstützt/verfügbar gemacht werden, da Verbindungen intern von dieser Instanz verwaltet werden
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DbParameterCollection">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbParameterCollection DbParameterCollection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.Common.DbParameterCollection DbParameterCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbParameterCollection" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property DbParameterCollection As DbParameterCollection" />
      <MemberSignature Language="F#" Value="member this.DbParameterCollection : System.Data.Common.DbParameterCollection" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbParameterCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbParameterCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Auflistung von "SqlParameter"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DbTransaction">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbTransaction DbTransaction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.Common.DbTransaction DbTransaction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbTransaction" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Property DbTransaction As DbTransaction" />
      <MemberSignature Language="F#" Value="member this.DbTransaction : System.Data.Common.DbTransaction with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbTransaction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbTransaction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Eigenschaft wird derzeit nicht unterstützt. Zugreifen auf die Eigenschaft führt zu einer Ausnahme.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DesignTimeVisible">
      <MemberSignature Language="C#" Value="public override bool DesignTimeVisible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DesignTimeVisible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DesignTimeVisible" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property DesignTimeVisible As Boolean" />
      <MemberSignature Language="F#" Value="member this.DesignTimeVisible : bool with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DesignTimeVisible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Eigenschaft wird derzeit nicht unterstützt. Zugreifen auf die Eigenschaft führt zu einer Ausnahme.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="multiShardCommand.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1031:DoNotCatchGeneralExceptionTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"></param>
        <summary>
            Deaktiviert alle reservierten nicht verwalteten/verwalteten Ressourcen freizugeben
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteDbDataReader">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbDataReader ExecuteDbDataReader (System.Data.CommandBehavior behavior);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Data.Common.DbDataReader ExecuteDbDataReader(valuetype System.Data.CommandBehavior behavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteDbDataReader(System.Data.CommandBehavior)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ExecuteDbDataReader (behavior As CommandBehavior) As DbDataReader" />
      <MemberSignature Language="F#" Value="override this.ExecuteDbDataReader : System.Data.CommandBehavior -&gt; System.Data.Common.DbDataReader" Usage="multiShardCommand.ExecuteDbDataReader behavior" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbDataReader</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="behavior" Type="System.Data.CommandBehavior" />
      </Parameters>
      <Docs>
        <param name="behavior">To be added.</param>
        <summary>
            - Führt die angegebene Abfrage für alle Shards und einen Reader, der Ergebnisse von ihnen umfasst zurück.
                - Verwendet die MultiShardExecutionPolicy.CompleteResults als die standardausführungsrichtlinie
            - Enthält die $ShardName Pseudo-Spalte in den Ergebnissen <param name="behavior">Befehl zu verwendende Verhalten</param><returns>MultiShardDataReader-Instanz, die Ergebnisse von allen Shards umfasst</returns><exception cref="T:System.InvalidOperationException">Wenn CommandText null ist oder leere</exception><exception cref="T:System.InvalidOperationException">ist das Verhalten des Befehls nicht unterstützte (CloseConnection oder SingleResult oder SingleRow)</exception><exception cref="T:System.TimeoutException">Wenn vor dem Abschluss der CommandTimeout vergangen</exception></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteDbDataReaderAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task&lt;System.Data.Common.DbDataReader&gt; ExecuteDbDataReaderAsync (System.Data.CommandBehavior behavior, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class System.Data.Common.DbDataReader&gt; ExecuteDbDataReaderAsync(valuetype System.Data.CommandBehavior behavior, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteDbDataReaderAsync(System.Data.CommandBehavior,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteDbDataReaderAsync : System.Data.CommandBehavior * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Common.DbDataReader&gt;" Usage="multiShardCommand.ExecuteDbDataReaderAsync (behavior, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Common.DbDataReader&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="behavior" Type="System.Data.CommandBehavior" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="behavior">Befehlsverhalten verwenden</param>
        <param name="cancellationToken">Abbruchtoken zum Abbrechen der Ausführung des Befehls</param>
        <summary>
            - Die angegebene Abfrage für alle Shards asynchron ausgeführt wird
            - Verwendet die MultiShardExecutionPolicy.CompleteResults als die standardausführungsrichtlinie
            - Enthält die $ShardName Pseudo-Spalte in den Ergebnissen
            </summary>
        <returns>Eine Aufgabe mit einem TResult enthält, die Ergebnisse von allen Shards umfasst</returns>
        <remarks>Ausnahmen während der Ausführung des Befehls werden über die zurückgegebene Aufgabe weitergegeben.</remarks>
        <exception cref="T:System.InvalidOperationException">Wenn die CommandText null oder leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteNonQuery">
      <MemberSignature Language="C#" Value="public override int ExecuteNonQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 ExecuteNonQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteNonQuery" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ExecuteNonQuery () As Integer" />
      <MemberSignature Language="F#" Value="override this.ExecuteNonQuery : unit -&gt; int" Usage="multiShardCommand.ExecuteNonQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ExecuteNonQuery wird derzeit nicht unterstützt.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteNonQueryAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;int&gt; ExecuteNonQueryAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ExecuteNonQueryAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteNonQueryAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteNonQueryAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="multiShardCommand.ExecuteNonQueryAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">das Abbruchtoken, das</param>
        <summary>
            "Executenonqueryasync" wird derzeit nicht unterstützt.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReader">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader ExecuteReader ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader ExecuteReader() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReader" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteReader () As MultiShardDataReader" />
      <MemberSignature Language="F#" Value="override this.ExecuteReader : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" Usage="multiShardCommand.ExecuteReader " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />. Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />. Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.
            </summary>
        <returns> die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet. </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">wird ausgelöst, wenn die CommandText null oder leer ist.</exception>
        <exception cref="T:System.TimeoutException">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout verstrichene</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReader">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader ExecuteReader (System.Data.CommandBehavior behavior);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader ExecuteReader(valuetype System.Data.CommandBehavior behavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReader(System.Data.CommandBehavior)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteReader (behavior As CommandBehavior) As MultiShardDataReader" />
      <MemberSignature Language="F#" Value="override this.ExecuteReader : System.Data.CommandBehavior -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" Usage="multiShardCommand.ExecuteReader behavior" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="behavior" Type="System.Data.CommandBehavior" />
      </Parameters>
      <Docs>
        <param name="behavior"> Gibt an, die <see cref="T:System.Data.CommandBehavior" /> verwenden.</param>
        <summary>
            ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />. Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />. Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.
            </summary>
        <returns> die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet. </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">wird ausgelöst, wenn CommandText null oder leer ist oder wenn das angegebene Befehlsverhalten z. B. CloseConnection oder SingleRow nicht unterstützt wird.</exception>
        <exception cref="T:System.TimeoutException">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout ist verstrichen.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReaderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReaderAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteReaderAsync () As Task(Of MultiShardDataReader)" />
      <MemberSignature Language="F#" Value="override this.ExecuteReaderAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;" Usage="multiShardCommand.ExecuteReaderAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />. Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />. Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.
            </summary>
        <returns> eine Aufgabe Warapping der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet. </returns>
        <remarks>Ausnahmen während der Ausführung des Befehls werden über die zurückgegebene Aufgabe weitergegeben.</remarks>
        <exception cref="T:System.InvalidOperationException">wird ausgelöst, wenn CommandText null oder leer ist oder wenn das angegebene Befehlsverhalten z. B. CloseConnection oder SingleRow nicht unterstützt wird.</exception>
        <exception cref="T:System.TimeoutException">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout ist verstrichen.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReaderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReaderAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteReaderAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;" Usage="multiShardCommand.ExecuteReaderAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Abbruchtoken zum Abbrechen der Ausführung des Befehls</param>
        <summary>
            ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />. Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />. Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.
            </summary>
        <returns> eine Aufgabe Warapping der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet. </returns>
        <remarks>Ausnahmen während der Ausführung des Befehls werden über die zurückgegebene Aufgabe weitergegeben.</remarks>
        <exception cref="T:System.InvalidOperationException">wird ausgelöst, wenn CommandText null oder leer ist oder wenn das angegebene Befehlsverhalten z. B. CloseConnection oder SingleRow nicht unterstützt wird.</exception>
        <exception cref="T:System.TimeoutException">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout ist verstrichen.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReaderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync (System.Data.CommandBehavior behavior, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync(valuetype System.Data.CommandBehavior behavior, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReaderAsync(System.Data.CommandBehavior,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteReaderAsync : System.Data.CommandBehavior * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;" Usage="multiShardCommand.ExecuteReaderAsync (behavior, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="behavior" Type="System.Data.CommandBehavior" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="behavior">Befehlsverhalten verwenden</param>
        <param name="cancellationToken">Abbruchtoken zum Abbrechen der Ausführung des Befehls</param>
        <summary>
            ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />. Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />. Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.
            </summary>
        <returns> eine Aufgabe Warapping der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet. </returns>
        <remarks>Ausnahmen während der Ausführung des Befehls werden über die zurückgegebene Aufgabe weitergegeben.</remarks>
        <exception cref="T:System.InvalidOperationException">wird ausgelöst, wenn CommandText null oder leer ist oder wenn das angegebene Befehlsverhalten z. B. CloseConnection oder SingleRow nicht unterstützt wird.</exception>
        <exception cref="T:System.TimeoutException">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout ist verstrichen.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteScalar">
      <MemberSignature Language="C#" Value="public override object ExecuteScalar ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance object ExecuteScalar() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteScalar" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ExecuteScalar () As Object" />
      <MemberSignature Language="F#" Value="override this.ExecuteScalar : unit -&gt; obj" Usage="multiShardCommand.ExecuteScalar " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ExecuteScalar wird derzeit nicht unterstützt.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteScalarAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;object&gt; ExecuteScalarAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; ExecuteScalarAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteScalarAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteScalarAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="multiShardCommand.ExecuteScalarAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">das Abbruchtoken, das</param>
        <summary>
            ExecuteScalarAsync wird derzeit nicht unterstützt.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions ExecutionOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions ExecutionOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecutionOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionOptions As MultiShardExecutionOptions" />
      <MemberSignature Language="F#" Value="member this.ExecutionOptions : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecutionOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die steuern, wie der Befehl ausgeführt wird.
            Beispielsweise können Sie dies verwenden, um den Shard-Namen als eine zusätzliche Spalte in das Ergebnis einzuschließen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy ExecutionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy ExecutionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecutionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionPolicy As MultiShardExecutionPolicy" />
      <MemberSignature Language="F#" Value="member this.ExecutionPolicy : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecutionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Ausführungsrichtlinie beim Ausführen von Befehlen auf Shards zu verwendende. Durch diese Richtlinie können Benutzer steuern, ob die vollständigen Ergebnisse erforderlich sind, oder gibt an, ob Teilergebnisse zulässig sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlParameterCollection Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.SqlClient.SqlParameterCollection Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As SqlParameterCollection" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Data.SqlClient.SqlParameterCollection" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlParameterCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die <see cref="T:System.Data.SqlClient.SqlParameterCollection" /> mit diesem Befehl verbunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prepare">
      <MemberSignature Language="C#" Value="public override void Prepare ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Prepare() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Prepare" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Prepare ()" />
      <MemberSignature Language="F#" Value="override this.Prepare : unit -&gt; unit" Usage="multiShardCommand.Prepare " />
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
            Diese Methode wird derzeit nicht unterstützt. Aufrufen der Eigenschaft, führt zu einer Ausnahme.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetCommandTimeout">
      <MemberSignature Language="C#" Value="public void ResetCommandTimeout ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetCommandTimeout() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ResetCommandTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetCommandTimeout ()" />
      <MemberSignature Language="F#" Value="member this.ResetCommandTimeout : unit -&gt; unit" Usage="multiShardCommand.ResetCommandTimeout " />
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
            Setzt die <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeout" /> Eigenschaft auf den Standardwert
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetCommandTimeoutPerShard">
      <MemberSignature Language="C#" Value="public void ResetCommandTimeoutPerShard ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetCommandTimeoutPerShard() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ResetCommandTimeoutPerShard" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetCommandTimeoutPerShard ()" />
      <MemberSignature Language="F#" Value="member this.ResetCommandTimeoutPerShard : unit -&gt; unit" Usage="multiShardCommand.ResetCommandTimeoutPerShard " />
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
            Setzt die <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeoutPerShard" /> Eigenschaft auf den Standardwert
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryBehavior">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior RetryBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior RetryBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.RetryBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryBehavior As RetryBehavior" />
      <MemberSignature Language="F#" Value="member this.RetryBehavior : Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.RetryBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Wiederholungsverhalten zum Erkennen von vorübergehenden Fehlern, die auftreten können, wenn eine Verbindung mit herstellen und Ausführen von Befehlen für einzelne Shards.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" /> ist die Standardeinstellung.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardExecutionBegan">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionBegan;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionBegan" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ShardExecutionBegan" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ShardExecutionBegan As EventHandler(Of ShardExecutionEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ShardExecutionBegan : EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " Usage="member this.ShardExecutionBegan : System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Ereignishandler wird aufgerufen, wenn die Ausführung auf einem bestimmten Shard begonnen wurde.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardExecutionCanceled">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionCanceled;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionCanceled" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ShardExecutionCanceled" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ShardExecutionCanceled As EventHandler(Of ShardExecutionEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ShardExecutionCanceled : EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " Usage="member this.ShardExecutionCanceled : System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Ereignishandler wird aufgerufen, wenn die Ausführung auf einem bestimmten Shard abgebrochen wird, entweder explizit über die bereitgestellte <see cref="T:System.Threading.CancellationToken" /> oder implizit als Ergebnis der ausgewählten <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardExecutionFaulted">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionFaulted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionFaulted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ShardExecutionFaulted" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ShardExecutionFaulted As EventHandler(Of ShardExecutionEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ShardExecutionFaulted : EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " Usage="member this.ShardExecutionFaulted : System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Ereignishandler wird aufgerufen, wenn die Ausführung auf einem bestimmten Shard einen Fehler verursacht hat. Dieser Handler wird nur aufgerufen, auf Ausnahmen für die Ausführung nicht Weitere daher wiederholt konnte die Ausnahme nicht-Transience oder aufgrund der ausgewählten <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.RetryBehavior" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardExecutionSucceeded">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionSucceeded;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionSucceeded" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ShardExecutionSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ShardExecutionSucceeded As EventHandler(Of ShardExecutionEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ShardExecutionSucceeded : EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " Usage="member this.ShardExecutionSucceeded : System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Ereignishandler wird aufgerufen, wenn die Ausführung erfolgreich abgeschlossen wurde, auf einem bestimmten Shard oder seine Shard-spezifische <see cref="T:System.Data.IDataReader" /> zurückgegeben wurde.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedRowSource">
      <MemberSignature Language="C#" Value="public override System.Data.UpdateRowSource UpdatedRowSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Data.UpdateRowSource UpdatedRowSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.UpdatedRowSource" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property UpdatedRowSource As UpdateRowSource" />
      <MemberSignature Language="F#" Value="member this.UpdatedRowSource : System.Data.UpdateRowSource with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.UpdatedRowSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.UpdateRowSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Eigenschaft wird derzeit nicht unterstützt. Zugreifen auf die Eigenschaft führt zu einer Ausnahme.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>