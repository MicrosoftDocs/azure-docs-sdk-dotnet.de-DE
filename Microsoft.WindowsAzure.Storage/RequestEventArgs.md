<Type Name="RequestEventArgs" FullName="Microsoft.WindowsAzure.Storage.RequestEventArgs">
  <TypeSignature Language="C#" Value="public sealed class RequestEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RequestEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RequestEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RequestEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type RequestEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt Informationen und jedes öffentliche Ereignis Daten, die mit einem Anforderungsereignis verknüpft ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestEventArgs (Microsoft.WindowsAzure.Storage.RequestResult res);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.RequestResult res) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RequestEventArgs.#ctor(Microsoft.WindowsAzure.Storage.RequestResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (res As RequestResult)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.RequestEventArgs : Microsoft.WindowsAzure.Storage.RequestResult -&gt; Microsoft.WindowsAzure.Storage.RequestEventArgs" Usage="new Microsoft.WindowsAzure.Storage.RequestEventArgs res" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="res" Type="Microsoft.WindowsAzure.Storage.RequestResult" />
      </Parameters>
      <Docs>
        <param name="res">Das <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.RequestEventArgs" /> Klasse unter Verwendung des angegebenen <see cref="T:Microsoft.WindowsAzure.Storage.RequestResult" /> Parameter.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public System.Net.HttpWebRequest Request { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.HttpWebRequest Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestEventArgs.Request" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Request As HttpWebRequest" />
      <MemberSignature Language="F#" Value="member this.Request : System.Net.HttpWebRequest" Usage="Microsoft.WindowsAzure.Storage.RequestEventArgs.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebRequest</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die diesem Ereignis zugeordnete HTTP-Anforderung ab.
            </summary>
        <value>Die diesem Ereignis zugeordnete HTTP-Anforderung.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestInformation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RequestResult RequestInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RequestResult RequestInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestEventArgs.RequestInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestInformation As RequestResult" />
      <MemberSignature Language="F#" Value="member this.RequestInformation : Microsoft.WindowsAzure.Storage.RequestResult" Usage="Microsoft.WindowsAzure.Storage.RequestEventArgs.RequestInformation" />
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
            Ruft die mit diesem Ereignis verknüpften Anforderungsinformationen ab.
            </summary>
        <value>Die Anforderungsinformationen, die dem Ereignis zugeordnet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Response">
      <MemberSignature Language="C#" Value="public System.Net.HttpWebResponse Response { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.HttpWebResponse Response" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RequestEventArgs.Response" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Response As HttpWebResponse" />
      <MemberSignature Language="F#" Value="member this.Response : System.Net.HttpWebResponse" Usage="Microsoft.WindowsAzure.Storage.RequestEventArgs.Response" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpWebResponse</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die diesem Ereignis zugeordnete HTTP-Antwort ab.
            </summary>
        <value>Die diesem Ereignis zugeordnete HTTP-Antwort.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>