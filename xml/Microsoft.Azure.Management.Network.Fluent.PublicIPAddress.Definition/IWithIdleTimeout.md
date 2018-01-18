<Type Name="IWithIdleTimeout" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithIdleTimeout">
  <TypeSignature Language="C#" Value="public interface IWithIdleTimeout" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdleTimeout" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithIdleTimeout" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdleTimeout" />
  <TypeSignature Language="F#" Value="type IWithIdleTimeout = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9fe82-101">Eine öffentliche IP-adressendefinition ermöglicht das Leerlauftimeout angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9fe82-101">A public IP address definition allowing the idle timeout to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithIdleTimeoutInMinutes (int minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithIdleTimeoutInMinutes(int32 minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithIdleTimeout.WithIdleTimeoutInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIdleTimeoutInMinutes (minutes As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithIdleTimeoutInMinutes : int -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithIdleTimeout.WithIdleTimeoutInMinutes minutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="minutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minutes"><span data-ttu-id="9fe82-102">Die Länge der Zeit in Minuten.</span><span class="sxs-lookup"><span data-stu-id="9fe82-102">The length of the time out in minutes.</span></span></param>
        <summary>
            <span data-ttu-id="9fe82-103">Gibt den Timeoutwert (in Minuten) für eine Verbindung im Leerlauf an.</span><span class="sxs-lookup"><span data-stu-id="9fe82-103">Specifies the timeout (in minutes) for an idle connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9fe82-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9fe82-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>