<Type Name="IWithPrimaryPublicIPAddress" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="F#" Value="type IWithPrimaryPublicIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Netzwerk Schnittstelle Definition zu ermöglichen, öffentliche IP-Adresse des primären IP-Konfiguration zugeordnet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingPrimaryPublicIPAddress (Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingPrimaryPublicIPAddress(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress.WithExistingPrimaryPublicIPAddress(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryPublicIPAddress (publicIPAddress As IPublicIPAddress) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryPublicIPAddress : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithPrimaryPublicIPAddress.WithExistingPrimaryPublicIPAddress publicIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="publicIPAddress">Eine vorhandene öffentliche IP-Adresse.</param>
        <summary>
            Ordnet eine vorhandene öffentliche IP-Adresse der Netzwerkschnittstelle primäre IP-Konfiguration.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse in derselben Region und demselben Gruppe wie die Ressource, und verknüpfen Sie sie mit der Netzwerkschnittstelle primäre IP-Konfiguration.
            den internen Namen und die DNS-Bezeichnung für die öffentliche IP-Adresse werden nicht mit dem Netzwerknamen der Schnittstelle abgeleitet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewPrimaryPublicIPAddress (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewPrimaryPublicIPAddress(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (creatable As ICreatable(Of IPublicIPAddress)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für eine neue öffentliche IP-Adresse.</param>
        <summary>
            Erstellen Sie eine neue öffentliche IP-Adresse der Netzwerkschnittstelle primäre IP-Konfiguration, basierend auf der bereitgestellten Definition zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewPrimaryPublicIPAddress (string leafDnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewPrimaryPublicIPAddress(string leafDnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (leafDnsLabel As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress leafDnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leafDnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leafDnsLabel">Die Blattebene des Domänennamens.</param>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse in derselben Region und demselben Gruppe wie die Ressource, mit der angegebenen DNS-Bezeichnung, und verknüpfen Sie sie mit der Netzwerkschnittstelle primäre IP-Konfiguration.
            Der interne Name für die öffentliche IP-Adresse wird von der DNS-Bezeichnung abgeleitet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>