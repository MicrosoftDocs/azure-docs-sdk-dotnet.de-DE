<Type Name="IWithPrimaryPublicIPAddress" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryPublicIPAddress" />
  <TypeSignature Language="F#" Value="type IWithPrimaryPublicIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Netzwerkschnittstelle aktualisieren zulassen, deren primäre IP-Konfiguration öffentliche IP-Adresse zugeordnet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithExistingPrimaryPublicIPAddress (Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithExistingPrimaryPublicIPAddress(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithExistingPrimaryPublicIPAddress(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryPublicIPAddress (publicIPAddress As IPublicIPAddress) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryPublicIPAddress : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithExistingPrimaryPublicIPAddress publicIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="publicIPAddress">Eine vorhandene öffentliche IP-Adresse.</param>
        <summary>
            Ordnet eine vorhandene öffentliche IP-Adresse der Netzwerkschnittstelle primäre IP-Konfiguration.
            Wenn Sie vorhanden ist wird, die öffentliche IP-Zuordnung und dann für diese entfernt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Netzwerk-Schnittstelle Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse in derselben Region und demselben Gruppe wie die Ressource, und verknüpfen Sie sie mit der Netzwerkschnittstelle primäre IP-Konfiguration.
            den internen Namen und die DNS-Bezeichnung für die öffentliche IP-Adresse werden von der Netzwerkschnittstellenname abgeleitet werden, wenn eine vorhandene öffentliche IP-Zuordnung vorhanden ist, und klicken Sie dann, die für diese entfernt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Netzwerk-Schnittstelle Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (creatable As ICreatable(Of IPublicIPAddress)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für eine neue öffentliche IP-Adresse.</param>
        <summary>
            Erstellen Sie eine neue öffentliche IP-Adresse um die Netzwerkschnittstelle primäre IP-Konfiguration, basierend auf der bereitgestellten Definition zuzuordnen.
            befindet sich öffentliche IP zugeordnete primäre IP-Konfiguration und, wird für diese entfernt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Netzwerk-Schnittstelle Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress (string leafDnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewPrimaryPublicIPAddress(string leafDnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (leafDnsLabel As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithNewPrimaryPublicIPAddress leafDnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leafDnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leafDnsLabel">Die Blattebene des Domänennamens.</param>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse in derselben Region und demselben Gruppe wie die Ressource, mit der angegebenen DNS-Bezeichnung, und verknüpfen Sie sie mit der Netzwerkschnittstelle primäre IP-Konfiguration.
            der interne Name für die öffentliche IP-Adresse wird von der DNS-Bezeichnung abgeleitet werden, wenn eine vorhandene öffentliche IP-Zuordnung vorhanden ist, und klicken Sie dann, die für diese entfernt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Netzwerk-Schnittstelle Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPublicIPAddress.WithoutPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryPublicIPAddress () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPublicIPAddress.WithoutPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass öffentliche IP-Adresse der Netzwerkschnittstelle primäre IP-Konfiguration zugeordneten entfernen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Netzwerk-Schnittstelle Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>