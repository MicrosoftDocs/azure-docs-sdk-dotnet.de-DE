<Type Name="IWithRoutingWeight" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingWeight">
  <TypeSignature Language="C#" Value="public interface IWithRoutingWeight" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingWeight" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingWeight" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoutingWeight" />
  <TypeSignature Language="F#" Value="type IWithRoutingWeight = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c4553-101">Die Phase des Traffic Manager-Profil Endpunkt Updates ermöglicht die Gewichtung Endpunkt angeben.</span><span class="sxs-lookup"><span data-stu-id="c4553-101">The stage of the traffic manager profile endpoint update allowing to specify the endpoint weight.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingWeight">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate WithRoutingWeight (int weight);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate WithRoutingWeight(int32 weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithRoutingWeight.WithRoutingWeight(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingWeight (weight As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingWeight : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate" Usage="iWithRoutingWeight.WithRoutingWeight weight" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="weight" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="weight"><span data-ttu-id="c4553-102">Die Endpunkt-Gewichtung.</span><span class="sxs-lookup"><span data-stu-id="c4553-102">The endpoint weight.</span></span></param>
        <summary>
            <span data-ttu-id="c4553-103">Gibt die Gewichtung für den Endpunkt, der verwendet wird, wenn die Gewichtung beruhende Routingmethode TrafficRoutingMethod.WEIGHTED für das Profil aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="c4553-103">Specifies the weight for the endpoint that will be used when the weight-based routing method TrafficRoutingMethod.WEIGHTED is enabled on the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c4553-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="c4553-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>