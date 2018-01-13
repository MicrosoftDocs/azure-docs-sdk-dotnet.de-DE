<Type Name="IWithDestinationAddressPrefix" FullName="Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithDestinationAddressPrefix">
  <TypeSignature Language="C#" Value="public interface IWithDestinationAddressPrefix" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationAddressPrefix" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithDestinationAddressPrefix" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationAddressPrefix" />
  <TypeSignature Language="F#" Value="type IWithDestinationAddressPrefix = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase einer Route Update ermöglichen das Zieladresspräfix ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate WithDestinationAddressPrefix (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate WithDestinationAddressPrefix(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.Update.IWithDestinationAddressPrefix.WithDestinationAddressPrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDestinationAddressPrefix (cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDestinationAddressPrefix : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate" Usage="iWithDestinationAddressPrefix.WithDestinationAddressPrefix cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr">Ein Adresspräfix, die in der CIDR-Schreibweise ausgedrückt wird.</param>
        <summary>
            Gibt das Zieladresspräfix, um die Route zu übernehmen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>