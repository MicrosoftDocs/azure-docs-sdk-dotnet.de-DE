<Type Name="MultiShardException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException">
  <TypeSignature Language="C#" Value="public class MultiShardException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MultiShardException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine MultiShardException stellt eine Ausnahme, die beim Ausführen von Vorgängen für einen Shard ist aufgetreten.
            Es bietet Informationen zu sowohl die Identität des Shards und die Ausnahme, die aufgetreten sind.
            Je nach Art der Ausnahme kann eine führen Sie erneut die Abfrage mit mehreren Shard, führen Sie eine separate Abfrage direkt auf den shardingmechanismus darauf ergab vermutet ausgerichtet oder schließlich führen Sie die Abfrage manuell für den Shard mit einem gemeinsamen Tool wie SSMS.  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MultiShardException-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException shardLocation" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
      </Parameters>
      <Docs>
        <param name="shardLocation"> Gibt den Speicherort des betreffenden Shards, in dem die Ausnahme aufgetreten ist.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> Klasse mit dem angegebenen Shard-Speicherort.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"> Gibt an, die an den Shard aufgetretene Ausnahme.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse MultiShardException mit der angegebenen Fehlermeldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (shardLocation, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="shardLocation"> Gibt den Speicherort des betreffenden Shards, in dem die Ausnahme aufgetreten ist.</param>
        <param name="inner"> Gibt an, die an den Shard aufgetretene Ausnahme.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> Klasse mit der angegebenen Shard Position und die Ausnahme.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (shardLocation, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shardLocation"> Gibt den Speicherort des betreffenden Shards, in dem die Ausnahme aufgetreten ist.</param>
        <param name="message"> auszuführenden Debuggerabbilds die Meldung, die die Ursache der Ausnahme erklärt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> Klasse mit dem angegebenen Shard Speicherort und Fehler.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
            Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> finden, die die serialisierten Objektdaten zur ausgelösten Ausnahme enthält.
            </param>
        <param name="context">
            Der <see cref="T:System.Runtime.Serialization.StreamingContext" />, der die Kontextinformationen über die Quelle oder das Ziel enthält.
            </param>
        <summary>
            Initialisiert eine neue Instanz der MultiShardException-Klasse mit serialisierten Daten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"> auszuführenden Debuggerabbilds die Meldung, die die Ursache der Ausnahme erklärt wird.</param>
        <param name="innerException"> Gibt an, die an den Shard aufgetretene Ausnahme.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse MultiShardException mit der angegebenen Fehlermeldung und der Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation shardLocation, string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation,System.String,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation * string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException (shardLocation, message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shardLocation" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="shardLocation"> Gibt den Speicherort des betreffenden Shards, in dem die Ausnahme aufgetreten ist.</param>
        <param name="message"> auszuführenden Debuggerabbilds die Meldung, die die Ursache der Ausnahme erklärt wird.</param>
        <param name="inner"> Gibt an, die an den Shard aufgetretene Ausnahme.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> Klasse mit der angegebenen Shard Position, die Fehlermeldung und die aufgetretene Ausnahme.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Die <paramref name="shardLocation" /> ist null. </exception>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="multiShardException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <see cref="T:System.Runtime.Serialization.SerializationInfo" />mit Daten zu füllende Objekt.</param>
        <param name="context">Das Ziel <see cref="T:System.Runtime.Serialization.StreamingContext" /> Objekt für diese Serialisierung.</param>
        <summary>
            Füllt die angegebene <see cref="T:System.Runtime.Serialization.SerializationInfo" /> Parameter mit den Daten, die zum Serialisieren des Zielobjekts erforderlich sind.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation ShardLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation ShardLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.ShardLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ShardLocation As ShardLocation" />
      <MemberSignature Language="F#" Value="member this.ShardLocation : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.ShardLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die dieser Ausnahme zugeordnete shard
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="multiShardException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine Zeichenfolgendarstellung der aktuellen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" /> und gibt diese zurück.
            </summary>
        <returns>Entspricht der Zeichenfolgendarstellung der aktuellen Ausnahme.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>