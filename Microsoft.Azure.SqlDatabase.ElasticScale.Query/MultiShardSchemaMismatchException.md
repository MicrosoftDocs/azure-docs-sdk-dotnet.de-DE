<Type Name="MultiShardSchemaMismatchException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException">
  <TypeSignature Language="C#" Value="public class MultiShardSchemaMismatchException : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardSchemaMismatchException extends Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardSchemaMismatchException&#xA;Inherits MultiShardException" />
  <TypeSignature Language="F#" Value="type MultiShardSchemaMismatchException = class&#xA;    inherit MultiShardException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Benutzerdefinierte Ausnahme wird ausgelöst, wenn das Schema für mindestens eine der Einbeziehung in die gesamte Abfrage Shards nicht das erwartete Schema für die Abfrage mit mehreren Shard als Ganzes entspricht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MultiShardSchemaMismatchException-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"> auszuführenden Debuggerabbilds die Meldung, die die Ursache der Ausnahme erklärt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse MultiShardSchemaMismatchException mit der angegebenen Fehlermeldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardSchemaMismatchException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException (info, context)" />
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
            Initialisiert eine neue Instanz der MultiShardSchemaMismatchException-Klasse mit serialisierten Daten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException (message, innerException)" />
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
            Initialisiert eine neue Instanz der Klasse MultiShardSchemaMismatchException mit der angegebenen Fehlermeldung und der Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>