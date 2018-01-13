<Type Name="RelayConnectionStringBuilder" FullName="Microsoft.Azure.Relay.RelayConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class RelayConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type RelayConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erstellt und verwaltet den Inhalt von Verbindungszeichenfolgen. Sie können diese Klasse verwenden, um eine Verbindungszeichenfolge für die Arbeit mit einem Relay-Namespace zu erstellen. Sie können auch die grundlegende Validierung auf eine vorhandene Verbindungszeichenfolge verwendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayConnectionStringBuilder ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayConnectionStringBuilder (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayConnectionStringBuilder : string -&gt; Microsoft.Azure.Relay.RelayConnectionStringBuilder" Usage="new Microsoft.Azure.Relay.RelayConnectionStringBuilder connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die Verbindungszeichenfolge, die aus dem Azure-Verwaltungsportal abgerufen werden können.</param>
        <summary>
            Initialisiert eine neue Instanz von einem <see cref="T:Microsoft.Azure.Relay.RelayConnectionStringBuilder" /> mit einer angegebenen vorhandenen Verbindungszeichenfolge.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn "ConnectionString" null oder leer ist.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
            Wird ausgelöst, wenn <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" /> ein nicht positiver Wert <see cref="T:System.TimeSpan" />.
            </exception>
        <exception cref="T:System.ArgumentException">
            Wird ausgelöst, wenn ein Schlüssel-Wert-Paar eines Schlüssels oder ein Wert vorhanden ist.
            Wird ausgelöst, wenn <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" /> angegeben ist, jedoch ist es sich nicht um einen gültigen absoluten <see cref="T:System.Uri" />.
            Wird ausgelöst, wenn <see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" /> angegeben ist, jedoch ist kein gültiger <see cref="T:System.TimeSpan" /> Format.
            Wird ausgelöst, wenn eine nicht unterstützte Schlüsselname angegeben wird.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public Uri Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.Endpoint : Uri with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Adresse des Relay-Namespace fest.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn der Endpunkt festgelegt wird auf Null.</exception>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn der Endpunkt festgelegt wird, um eine <see cref="T:System.Uri" /> absolut ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Pfad für die Entität für die HybridConnection fest.</summary>
        <value>Gibt den Pfad für die Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die <see cref="T:System.TimeSpan" /> , die angibt, wie lange die bleibt, bevor ein Timeout eintritt.</summary>
        <value>Der <see cref="T:System.TimeSpan" />-Wert, der angibt, welcher Zeitraum für den Vorgang verbleibt, bevor ein Timeout auftritt. Der Standardwert ist eine Minute.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn OperationTimeout auf einen nicht positiven TimeSpan-Wert festgelegt ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den SAS-Schlüssel für die Verbindungsauthentifizierung fest.</summary>
        <value>Der SAS-Schlüssel für die Verbindungsauthentifizierung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Namen des SAS-Schlüssels.</summary>
        <value>Der Name des SAS-Schlüssels.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string with get, set" Usage="Microsoft.Azure.Relay.RelayConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das SAS-Token.</summary>
        <value>Gibt das konfigurierte SAS-Token.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="relayConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt eine "ConnectionString", die das aktuelle Objekt darstellt.</summary>
        <returns>Eine "ConnectionString", die das aktuelle Objekt darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>