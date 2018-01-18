<Type Name="IWithPath" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithPath">
  <TypeSignature Language="C#" Value="public interface IWithPath" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPath" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithPath" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPath" />
  <TypeSignature Language="F#" Value="type IWithPath = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6726b-101">Die Phase einer Anwendung Gateway Prüfpunkt Update zu ermöglichen, geben Sie den Pfad, um die Überprüfung zu senden.</span><span class="sxs-lookup"><span data-stu-id="6726b-101">Stage of an application gateway probe update allowing to specify the path to send the probe to.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPath">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithPath (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithPath(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithPath.WithPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPath (path As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPath : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate" Usage="iWithPath.WithPath path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="6726b-102">Ein relativer Pfad.</span><span class="sxs-lookup"><span data-stu-id="6726b-102">A relative path.</span></span></param>
        <summary>
            <span data-ttu-id="6726b-103">Gibt den relativen Pfad für den Prüfpunkt aufrufen.</span><span class="sxs-lookup"><span data-stu-id="6726b-103">Specifies the relative path for the probe to call.</span></span>
            <span data-ttu-id="6726b-104">Ein Prüfpunkt wird gesendet, um &lt;Protokoll&gt;://&lt;Host&gt;:&lt;Port&gt;&lt;Pfad&gt;.</span><span class="sxs-lookup"><span data-stu-id="6726b-104">A probe is sent to &lt;protocol&gt;://&lt;host&gt;:&lt;port&gt;&lt;path&gt;.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6726b-105">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="6726b-105">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>