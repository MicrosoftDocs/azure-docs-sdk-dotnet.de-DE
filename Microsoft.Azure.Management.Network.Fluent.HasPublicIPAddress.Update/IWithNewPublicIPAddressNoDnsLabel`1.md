<Type Name="IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewPublicIPAddressNoDnsLabel`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewPublicIPAddressNoDnsLabel(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithNewPublicIPAddressNoDnsLabel&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT">die nächste Phase der Definition.</typeparam>
    <summary>
            Die Phase des Updates, sodass eine neue öffentliche IP-Adresse die Ressource zugeordnet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithNewPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithNewPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel`1.WithNewPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPublicIPAddress () As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithNewPublicIPAddress : unit -&gt; 'ReturnT" Usage="iWithNewPublicIPAddressNoDnsLabel.WithNewPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse in derselben Region und demselben Gruppe wie die Ressource, und ordnet die Ressource.
            Den internen Namen und die DNS-Bezeichnung für die öffentliche IP-Adresse werden der Name der Ressource abgeleitet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithNewPublicIPAddress (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithNewPublicIPAddress(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel`1.WithNewPublicIPAddress(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPublicIPAddress (creatable As ICreatable(Of IPublicIPAddress)) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithNewPublicIPAddress : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; -&gt; 'ReturnT" Usage="iWithNewPublicIPAddressNoDnsLabel.WithNewPublicIPAddress creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für eine neue öffentliche IP-Adresse.</param>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse der Ressource zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>