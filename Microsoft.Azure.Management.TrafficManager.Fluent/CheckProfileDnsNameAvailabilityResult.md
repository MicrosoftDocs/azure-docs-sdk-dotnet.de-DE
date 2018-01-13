<Type Name="CheckProfileDnsNameAvailabilityResult" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult">
  <TypeSignature Language="C#" Value="public class CheckProfileDnsNameAvailabilityResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckProfileDnsNameAvailabilityResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckProfileDnsNameAvailabilityResult" />
  <TypeSignature Language="F#" Value="type CheckProfileDnsNameAvailabilityResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="680d4-101">Das Aktionsergebnis com.microsoft.azure.management.trafficmanager.TrafficManagerProfiles.checkDnsNameAvailability.</span><span class="sxs-lookup"><span data-stu-id="680d4-101">The com.microsoft.azure.management.trafficmanager.TrafficManagerProfiles.checkDnsNameAvailability action result.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckProfileDnsNameAvailabilityResult (Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult.#ctor(Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (inner As TrafficManagerNameAvailabilityInner)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult : Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult" Usage="new Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult inner" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="inner" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner" />
      </Parameters>
      <Docs>
        <param name="inner"><span data-ttu-id="680d4-102">Das innere Objekt.</span><span class="sxs-lookup"><span data-stu-id="680d4-102">The inner object.</span></span></param>
        <summary>
             <span data-ttu-id="680d4-103">Erstellt eine Instanz des CheckProfileDnsNameAvailabilityResult.</span><span class="sxs-lookup"><span data-stu-id="680d4-103">Creates an instance of CheckProfileDnsNameAvailabilityResult.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAvailable">
      <MemberSignature Language="C#" Value="public bool IsAvailable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsAvailable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult.IsAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Function IsAvailable () As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAvailable : unit -&gt; bool" Usage="checkProfileDnsNameAvailabilityResult.IsAvailable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="680d4-104">"true", wenn der DNS-Name für die Nutzung, False ist, wenn der Name bereits vergeben ist oder ungültige verfügbar und kann nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="680d4-104">True if the DNS name is available to use, false if the name has already been taken or invalid and cannot be used.</span></span>
            </return>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string Message() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult.Message" />
      <MemberSignature Language="VB.NET" Value="Public Function Message () As String" />
      <MemberSignature Language="F#" Value="member this.Message : unit -&gt; string" Usage="checkProfileDnsNameAvailabilityResult.Message " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680d4-105">Eine Fehlermeldung, die den Wert für den Grund im Detail erläutert.</span><span class="sxs-lookup"><span data-stu-id="680d4-105">An error message explaining the reason value in more detail.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.ProfileDnsNameUnavailableReason Reason ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.TrafficManager.Fluent.ProfileDnsNameUnavailableReason Reason() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.CheckProfileDnsNameAvailabilityResult.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Function Reason () As ProfileDnsNameUnavailableReason" />
      <MemberSignature Language="F#" Value="member this.Reason : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.ProfileDnsNameUnavailableReason" Usage="checkProfileDnsNameAvailabilityResult.Reason " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.ProfileDnsNameUnavailableReason</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="680d4-106">Der Grund, dass der DNS-Name konnte nicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="680d4-106">The reason that the DNS name could not be used.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>