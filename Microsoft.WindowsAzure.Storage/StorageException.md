<Type Name="StorageException" FullName="Microsoft.WindowsAzure.Storage.StorageException">
  <TypeSignature Language="C#" Value="public class StorageException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit StorageException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.StorageException" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type StorageException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine von der Azure Storage-Dienst ausgelöste Ausnahme dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : string -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die Meldung, in der der Fehler beschrieben wird.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />-Klasse mit der angegebenen Fehlermeldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StorageException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</param>
        <param name="context">Der <see cref="T:System.Runtime.Serialization.StreamingContext" />, der die Kontextinformationen über die Quelle oder das Ziel enthält.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />-Klasse mit serialisierten Daten.
            </summary>
        <remarks>Dieser Konstruktor wird während der Deserialisierung aufgerufen, um das über einen Stream übertragene Ausnahmeobjekt wiederherzustellen.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : string * Exception -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">Die Fehlermeldung "Ausnahme".</param>
        <param name="innerException">Die innere Ausnahme.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme generiert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageException (Microsoft.WindowsAzure.Storage.RequestResult res, string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.RequestResult res, string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.#ctor(Microsoft.WindowsAzure.Storage.RequestResult,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (res As RequestResult, message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.StorageException : Microsoft.WindowsAzure.Storage.RequestResult * string * Exception -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="new Microsoft.WindowsAzure.Storage.StorageException (res, message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="res" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="res">Das Ergebnis der Anforderung.</param>
        <param name="message">Die Ausnahmemeldung.</param>
        <param name="inner">Die innere Ausnahme.</param>
        <summary>
            Initialisiert mit den angegebenen Parametern eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="storageException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">Das mit Daten aufzufüllende <see cref="T:System.Runtime.Serialization.SerializationInfo" />-Objekt.</param>
        <param name="context">Der Zielkontext für diese Serialisierung.</param>
        <summary>
            Füllt ein <see cref="T:System.Runtime.Serialization.SerializationInfo" />-Objekt mit den Daten, die zum Serialisieren des Zielobjekts erforderlich sind.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestInformation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RequestResult RequestInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RequestResult RequestInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.StorageException.RequestInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestInformation As RequestResult" />
      <MemberSignature Language="F#" Value="member this.RequestInformation : Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.StorageException.RequestInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RequestResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> für dieses Objekt <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> Objekt.
            </summary>
        <value>Die <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> für dieses Objekt <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" /> Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="storageException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Stellt eine von der Microsoft Azure Storage Client Library ausgelöste Ausnahme dar. 
            </summary>
        <returns>Eine Zeichenfolge, die die Ausnahme darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TranslateException">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageException TranslateException (Exception ex, Microsoft.WindowsAzure.Storage.RequestResult reqResult);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageException TranslateException(class System.Exception ex, class Microsoft.WindowsAzure.Storage.RequestResult reqResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.TranslateException(System.Exception,Microsoft.WindowsAzure.Storage.RequestResult)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TranslateException (ex As Exception, reqResult As RequestResult) As StorageException" />
      <MemberSignature Language="F#" Value="static member TranslateException : Exception * Microsoft.WindowsAzure.Storage.RequestResult -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="Microsoft.WindowsAzure.Storage.StorageException.TranslateException (ex, reqResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageException</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ex" Type="System.Exception" />
        <Parameter Name="reqResult" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
      </Parameters>
      <Docs>
        <param name="ex">Die Ausnahme zu übersetzen.</param>
        <param name="reqResult">Das Ergebnis der Anforderung.</param>
        <summary>
            Übersetzt die angegebene Ausnahme in einem <see cref="T:Microsoft.WindowsAzure.Storage.StorageException" />.
            </summary>
        <returns>Die Speicher-Ausnahme.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TranslateException">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.StorageException TranslateException (Exception ex, Microsoft.WindowsAzure.Storage.RequestResult reqResult, Func&lt;System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; parseError);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.StorageException TranslateException(class System.Exception ex, class Microsoft.WindowsAzure.Storage.RequestResult reqResult, class System.Func`2&lt;class System.IO.Stream, class Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; parseError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.StorageException.TranslateException(System.Exception,Microsoft.WindowsAzure.Storage.RequestResult,System.Func{System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TranslateException (ex As Exception, reqResult As RequestResult, parseError As Func(Of Stream, StorageExtendedErrorInformation)) As StorageException" />
      <MemberSignature Language="F#" Value="static member TranslateException : Exception * Microsoft.WindowsAzure.Storage.RequestResult * Func&lt;System.IO.Stream, Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt; -&gt; Microsoft.WindowsAzure.Storage.StorageException" Usage="Microsoft.WindowsAzure.Storage.StorageException.TranslateException (ex, reqResult, parseError)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageException</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ex" Type="System.Exception" />
        <Parameter Name="reqResult" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
        <Parameter Name="parseError" Type="System.Func&lt;System.IO.Stream,Microsoft.WindowsAzure.Storage.StorageExtendedErrorInformation&gt;" />
      </Parameters>
      <Docs>
        <param name="ex">Die Ausnahme zu übersetzen.</param>
        <param name="reqResult">Das Ergebnis der Anforderung.</param>
        <param name="parseError">Der Delegat verwendet, um den Fehler zu analysieren, erweiterte Fehlerinformationen abzurufen.</param>
        <summary>
            Übersetzt die angegebene Ausnahme in einem Speicher-Ausnahme.
            </summary>
        <returns>Die Speicher-Ausnahme.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>