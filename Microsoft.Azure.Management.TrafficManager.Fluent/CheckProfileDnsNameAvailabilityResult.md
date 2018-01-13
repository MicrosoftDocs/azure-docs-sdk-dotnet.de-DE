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
             Das Aktionsergebnis com.microsoft.azure.management.trafficmanager.TrafficManagerProfiles.checkDnsNameAvailability.
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
        <param name="inner">Das innere Objekt.</param>
        <summary>
             Erstellt eine Instanz des CheckProfileDnsNameAvailabilityResult.
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
            "true", wenn der DNS-Name für die Nutzung, False ist, wenn der Name bereits vergeben ist oder ungültige verfügbar und kann nicht verwendet werden.
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
        <return>Eine Fehlermeldung, die den Wert für den Grund im Detail erläutert.</return>
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
        <return>Der Grund, dass der DNS-Name konnte nicht verwendet werden.</return>
      </Docs>
    </Member>
  </Members>
</Type>