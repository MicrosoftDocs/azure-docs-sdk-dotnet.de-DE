<Type Name="StaticConfigurationManager&lt;T&gt;" FullName="Microsoft.IdentityModel.Protocols.StaticConfigurationManager&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class StaticConfigurationManager&lt;T&gt; : Microsoft.IdentityModel.Protocols.IConfigurationManager&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StaticConfigurationManager`1&lt;class T&gt; extends System.Object implements class Microsoft.IdentityModel.Protocols.IConfigurationManager`1&lt;!T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1" />
  <TypeSignature Language="VB.NET" Value="Public Class StaticConfigurationManager(Of T)&#xA;Implements IConfigurationManager(Of T)" />
  <TypeSignature Language="F#" Value="type StaticConfigurationManager&lt;'T (requires 'T : null)&gt; = class&#xA;    interface IConfigurationManager&lt;'T (requires 'T : null)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Protocols.IConfigurationManager&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">eine Klasse muss sein.</typeparam>
    <summary>
            Dieser Typ ist für Benutzer, die eine feste und statische Konfiguration werden soll.
            In diesem Fall wird die Konfiguration abgerufen und an den Konstruktor übergeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StaticConfigurationManager (T configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configuration As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Protocols.StaticConfigurationManager&lt;'T (requires 'T : null)&gt; : 'T -&gt; Microsoft.IdentityModel.Protocols.StaticConfigurationManager&lt;'T (requires 'T : null)&gt;" Usage="new Microsoft.IdentityModel.Protocols.StaticConfigurationManager&lt;'T (requires 'T : null)&gt; configuration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configuration" Type="T" />
      </Parameters>
      <Docs>
        <param name="configuration">Konfiguration des Typs OpenIdConnectConfiguration oder OpenIdConnectConfiguration.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1" /> mit einer konfigurationsinstanz.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetConfigurationAsync (System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetConfigurationAsync(valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1.GetConfigurationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationAsync (cancel As CancellationToken) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt;&#xA;override this.GetConfigurationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt;" Usage="staticConfigurationManager.GetConfigurationAsync cancel" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IConfigurationManager`1.GetConfigurationAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancel">
          <see cref="T:System.Threading.CancellationToken" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</param>
        <summary>
            Ruft eine aktualisierte Version der Konfiguration ab.
            </summary>
        <returns>Konfiguration des Typs t</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRefresh">
      <MemberSignature Language="C#" Value="public void RequestRefresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RequestRefresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1.RequestRefresh" />
      <MemberSignature Language="VB.NET" Value="Public Sub RequestRefresh ()" />
      <MemberSignature Language="F#" Value="abstract member RequestRefresh : unit -&gt; unit&#xA;override this.RequestRefresh : unit -&gt; unit" Usage="staticConfigurationManager.RequestRefresh " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IConfigurationManager`1.RequestRefresh</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Für diesen Typ, dies ist nicht möglich
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>