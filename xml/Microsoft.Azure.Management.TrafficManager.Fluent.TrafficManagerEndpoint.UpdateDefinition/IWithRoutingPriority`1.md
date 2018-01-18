<Type Name="IWithRoutingPriority&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRoutingPriority&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingPriority`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoutingPriority(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRoutingPriority&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="3ccd9-101">Der Rückgabetyp der WithAttach.attach().</span><span class="sxs-lookup"><span data-stu-id="3ccd9-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="3ccd9-102">Die Phase der Traffic Manager Endpunktdefinition ermöglicht die endpunktpriorität angeben.</span><span class="sxs-lookup"><span data-stu-id="3ccd9-102">The stage of the traffic manager endpoint definition allowing to specify the endpoint priority.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithRoutingPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithRoutingPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithRoutingPriority`1.WithRoutingPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingPriority (priority As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingPriority : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRoutingPriority.WithRoutingPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority">
            <span data-ttu-id="3ccd9-103">die Priorität dieses Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="3ccd9-103">Priority of this endpoint.</span></span> <span data-ttu-id="3ccd9-104">Mögliche Werte liegen zwischen 1 und 1000, niedrigere Werte stellen eine höheren Priorität dar.</span><span class="sxs-lookup"><span data-stu-id="3ccd9-104">Possible values are from 1 to 1000, lower values represent higher priority.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ccd9-105">Gibt die Gewichtung für den Endpunkt, der verwendet wird, wenn der Routingmethode prioritätsbasierten TrafficRoutingMethod.PRIORITY auf das Profil aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="3ccd9-105">Specifies the weight for the endpoint that will be used when priority-based routing method is  TrafficRoutingMethod.PRIORITY enabled on the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3ccd9-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="3ccd9-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>